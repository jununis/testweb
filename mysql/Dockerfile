FROM mysql

ENV MYSQL_ROOT_PASSWORD=my-secret-pw
ENV MYSQL_DATABASE=mydb
ENV MYSQL_USER=myuser
ENV MYSQL_PASSWORD=myuserpassword

COPY ./my-database.sql /docker-entrypoint-initdb.d/

EXPOSE 3333