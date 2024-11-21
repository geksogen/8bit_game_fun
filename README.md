# 8bit_game_fun

#### Requirements
* Ubuntu v22.04 (2CPU, 20GB HDD, 4Gb RAM)
* 1 VM

#### Run
```BASH
docker build --platform="linux/amd64" --build-arg GAME_TAG=dyna --build-arg GAME_URL=https://archive.org/download/chenall_dyna/dyna.zip --build-arg GAME_ARGS=\"dyna.exe\" -t mycool:bomberman .
docker run --rm -p <ip>:8000:8000 mycool:bomberman
```
