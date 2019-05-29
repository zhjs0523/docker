FROM redis:5.0.3
EXPOSE 6379
ADD redis.conf /redis.conf
ENTRYPOINT [ "redis-server", "/redis.conf" ]

