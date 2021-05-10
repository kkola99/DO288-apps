FROM mysql:latest

ENV MYSQL_DATABSE day7
ENV MYSQL_USER razvan
ENV MYSQL_PASSWORD admin
ENV MYSQL_ROOT_PASSWORD Admin


RUN mkdir mysql
WORKDIR /mysql

COPY test.sql /mysql/test.sql
RUN /mysql/test.sql
