# Local commands

Build the demo image:

```bash
docker build -t int3105-docker-demo .
```

Run it and remove the container when it exits:

```bash
docker run --rm int3105-docker-demo
```

List the locally built image:

```bash
docker image ls int3105-docker-demo
```
