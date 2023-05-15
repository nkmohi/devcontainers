# Dev Container Slides

## Build:

```bash
docker run --rm -v $PWD:/home/marp/app/ -e LANG=$LANG -e MARP_USER="$(id -u):$(id -g)" marpteam/marp-cli slide-deck.md
```
