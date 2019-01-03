FROM mysql:5.7
ENV TZ=Asia/Shanghai
RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone
COPY db/install.sql /docker-entrypoint-initdb.d