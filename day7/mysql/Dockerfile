FROM mysql:latest

COPY . .

ENV MYSQL_DATABASE test
ENV MYSQL_USER razvan
ENV MYSQL_PASSWORD admin
ENV MYSQL_ROOT_PASSWORD Admin

ADD test.sql /docker-entrypoint-initdb.d
