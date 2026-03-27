SHELL := /bin/bash
DEV_IMAGE_TAG = "localhost/ucl-arc/research-data-isms-site:dev"
RELEASE_IMAGE_TAG = "localhost/ucl-arc/research-data-isms-site:release"

.PHONY: *

dev: ## Run the local development server in a docker container
	cd .. && docker build -t $(DEV_IMAGE_TAG) --target dev -f site/Dockerfile .
	docker run -it --rm \
	  -v $${PWD}/../docs/Controlled_Documents:/hugo/content \
	  -v $${PWD}/layouts:/hugo/layouts \
	  -p 1313:1313 \
	  $(DEV_IMAGE_TAG)
