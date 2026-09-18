# Troubleshooting

## Docker daemon is unavailable

Start Docker Desktop, then verify the daemon with:

```bash
docker info
```

## Rebuild without cached layers

```bash
docker build --no-cache -t int3105-docker-demo .
```

## Inspect a failed run

Open an interactive shell in the image:

```bash
docker run --rm -it --entrypoint /bin/sh int3105-docker-demo
```
