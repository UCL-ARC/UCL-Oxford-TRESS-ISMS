## --------------------------------------------------------
FROM ubuntu:latest AS hugo

ARG HUGO_VERSION="0.140.2"
ARG HUGO_BOOK_THEME_COMMIT="7c78a39c531aa2492ed7e92f2ce9dfb2c8c0d3fa"

SHELL ["/bin/bash", "-c"]

WORKDIR /hugo

RUN apt-get update && \
  apt-get install -y --no-install-recommends \
    wget \
    unzip \
    ca-certificates

RUN ARCH="$(uname -m)" && \
  if [ "$ARCH" == "aarch64" ]; then \
    wget https://github.com/gohugoio/hugo/releases/download/v${HUGO_VERSION}/hugo_extended_${HUGO_VERSION}_linux-arm64.deb; \
  else \
    wget https://github.com/gohugoio/hugo/releases/download/v${HUGO_VERSION}/hugo_extended_${HUGO_VERSION}_linux-amd64.deb; \
  fi && \
  dpkg -i *.deb

RUN hugo new site . --force &&\
  wget -O book.zip "https://github.com/alex-shpak/hugo-book/archive/${HUGO_BOOK_THEME_COMMIT}.zip" && \
  unzip book.zip && \
  mv hugo-book-* themes/hugo-book

COPY site/hugo.toml hugo.toml
COPY site/layouts layouts
COPY docs/Controlled_Documents content
RUN hugo --config hugo.toml && \
  rm -r public/katex

## --------------------------------------------------------
FROM hugo AS dev

WORKDIR /hugo
COPY site/hugo.toml hugo.toml

EXPOSE 1313
CMD ["hugo", "server", "--minify", "-D", "--bind", "0.0.0.0", "--config", "hugo.toml"]
