# Website

The ISMS is built into a UCL-facing website using [hugo](https://gohugo.io/)
to convert markdown into HTML, built into a container and served by
[gin](https://github.com/gin-gonic/gin). It's deployed into the TRE cluster
with an auto-update interval <1 day.

## Local development

In this directory, run

```bash
make dev
```

to build and run a hot-reloading container with the site in, then go to http://localhost:1313.
