FROM mysql
COPY ./db.sql /docker-entrypoint-initdb.d/
ENV MYSQL_USER root
ENV MYSQL_ALLOW_EMPTY_PASSWORD true 
