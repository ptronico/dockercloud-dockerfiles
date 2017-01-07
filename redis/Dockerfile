FROM redis:3.2.0
COPY redis.conf /usr/local/etc/redis/redis.conf
COPY docker-entrypoint.sh docker-entrypoint.sh
ENTRYPOINT ["docker-entrypoint.sh"]
