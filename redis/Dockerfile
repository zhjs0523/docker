FROM ubuntu
RUN apt-get update && apt-get install -y redis-server
RUN mkdir /root/redis
COPY redis.conf /etc/redis/redis.conf
RUN chmod 777 -R /root/redis
EXPOSE 6379
