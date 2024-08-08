FROM redis:7.4
RUN mkdir -p /opt/conf
COPY redis.conf /opt/conf/redis.conf
CMD ["redis-server", "/opt/conf/redis.conf"]