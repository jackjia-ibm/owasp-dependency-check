# owasp-dependency-check

This is a replica of https://hub.docker.com/r/owasp/dependency-check/dockerfile which fixes small issues in the Dockerfile.

## Fixes

- unzip not found during build
- VOLUME definition, which will see mount point of `[/src` and `/report]`.

## Build & Publish

```
docker build -t jackjiaibm/owasp-dependency-check .
docker push jackjiaibm/owasp-dependency-check
```
