FROM redis:6.2.6-bullseye

COPY config/redis.conf.default /usr/local/etc/redis/redis.conf

RUN usermod  -u 1001 redis
RUN groupmod -g 1001 redis
