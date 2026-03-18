# hello-world

## Pulling the Docker Image

You can pull the `hello-world` image from either the GitHub Container Registry (GHCR) or Docker Hub.

### From GitHub Container Registry

```bash
docker pull ghcr.io/shadaxtell-eng/hello-world:latest
```

### From Docker Hub

```bash
docker pull shadaxtell-eng/hello-world:latest
```

## Running the Image

You can run the image from either registry:

```bash
# Run from GitHub Container Registry
docker run --rm ghcr.io/shadaxtell-eng/hello-world:latest

# Run from Docker Hub
docker run --rm shadaxtell-eng/hello-world:latest
```