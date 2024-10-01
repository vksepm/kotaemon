kotaemon


```sh
docker run \
-e GRADIO_SERVER_NAME=0.0.0.0 \
-e GRADIO_SERVER_PORT=7860 \
-p 7860:7860 -it --rm \
ghcr.io/cinnamon/kotaemon:main-full
```

```sh
docker run \
--env-file .env \
-p 7860:7860 -it --rm \
ghcr.io/cinnamon/kotaemon:main-full
```

```
docker run \
--cpus="2" \
--env-file .env \
-p 7860:7860 -it --rm \
ghcr.io/cinnamon/kotaemon:main-full
```
