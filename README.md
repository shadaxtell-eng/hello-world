# hello-world

## Pulling the Docker Image

You can pull the `hello-world` image from the GitHub Container Registry using the following command:

```bash
docker pull ghcr.io/shadaxtell-eng/hello-world:latest
```

Or from Docker Hub:

```bash
docker pull shadaxtell-eng/hello-world:latest
```

## Running the Image

Once pulled, run the image with:

```bash
docker run --rm ghcr.io/shadaxtell-eng/hello-world:latest
```

Or, if you pulled from Docker Hub:

```bash
docker run --rm shadaxtell-eng/hello-world:latest
```