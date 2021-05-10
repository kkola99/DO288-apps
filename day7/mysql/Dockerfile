FROM mysql:8.0.24

ENV MYSQL_DATABSE test
ENV MYSQL_USER razvan
ENV MYSQL_PASSWORD admin
ENV MYSQL_ROOT_PASSWORD Admin

ADD test.sql /docker-entrypoint-initdb.d
