# Search My Stuff

## Steps

#### Install [Sonic](https://github.com/valeriansaliou/sonic)

These instructions are for Docker. For other installation methods, refer to [the guide on Sonic's Github repo.](https://github.com/valeriansaliou/sonic#installation)

```bash
docker pull valeriansaliou/sonic:v1.3.0
docker run -d -p 1491:1491 -v $PWD/sonic/config.cfg:/etc/sonic.cfg -v $PWD/sonic/store/:/var/lib/sonic/store/ valeriansaliou/sonic:v1.3.0

```
