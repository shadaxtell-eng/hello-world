# hello-world

## How to Pull a Docker Image from This Repository

This repository publishes Docker images to the [GitHub Container Registry (GHCR)](https://ghcr.io).

### Prerequisites

- [Docker](https://docs.docker.com/get-docker/) installed on your machine.

### Steps

1. **Authenticate with the GitHub Container Registry**

   You need a [GitHub Personal Access Token (PAT)](https://github.com/settings/tokens) with at least the `read:packages` scope.

   ```bash
   echo YOUR_GITHUB_TOKEN | docker login ghcr.io -u YOUR_GITHUB_USERNAME --password-stdin
   ```

2. **Pull the image**

   ```bash
   docker pull ghcr.io/shadaxtell-eng/hello-world:latest
   ```

3. **Run the image**

   ```bash
   docker run ghcr.io/shadaxtell-eng/hello-world:latest
   ```

### Pulling a Specific Version

To pull a specific tagged version instead of `latest`:

```bash
docker pull ghcr.io/shadaxtell-eng/hello-world:v1.0.0
```

### More Information

- [Working with the GitHub Container Registry](https://docs.github.com/en/packages/working-with-a-github-packages-registry/working-with-the-container-registry)
- [Authenticating to GitHub Packages](https://docs.github.com/en/packages/working-with-a-github-packages-registry/working-with-the-container-registry#authenticating-to-the-container-registry)