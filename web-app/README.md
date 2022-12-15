# NextJS with Redis 

[![Built with Devbox](https://jetpack.io/devbox/img/shield_galaxy.svg)](https://jetpack.io/devbox/docs/contributor-quickstart/)

Example devbox for testing and developing NextJS apps, and for running a local redis instance.

## Starting Redis

```bash
devbox run redis
```

This will run the Redis script, which will start the locally running redis instance for testing. The configuration file is found in `conf/redis/redis.conf`.

## Starting a Devbox Shell

```bash
devbox shell
```

This will activate a shell with all your dependencies installed. You can use this to run `redis-cli`, or to start and develop your NextJS app.

