# hello-world

## Pulling the Docker Image

This repository publishes a Docker image to the [GitHub Container Registry](https://ghcr.io).

### Pull the image

```bash
docker pull ghcr.io/shadaxtell-eng/hello-world:latest
```

### Run the image

```bash
docker run --rm ghcr.io/shadaxtell-eng/hello-world:latest
```

> **Note:** The image is automatically built and pushed to `ghcr.io` whenever changes are pushed to the `main` branch via the [Publish Docker Image](.github/workflows/docker-publish.yml) workflow.