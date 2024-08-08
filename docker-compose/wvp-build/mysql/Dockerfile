FROM mysql:8.4.2
# 复制初始化SQL脚本到容器中
COPY *.sql /docker-entrypoint-initdb.d/
# 设置环境变量
ENV MYSQL_ROOT_PASSWORD=123456
