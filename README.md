# Redis

Docker images containing Redis (v6.2.6) and Redis Commander (latest).

## Config files

- `main/redis/config/redis.conf.default` is default config suitable for the local environment.
It is copied during the docker build and is a part of the docker image.

- `main/redis/config/redis.conf` is config suitable for the various Landed environments.
The version in the develop branch is mounted dusing container start in the staging environment.
The version in the main branch is mounted during container start in the production environment.
