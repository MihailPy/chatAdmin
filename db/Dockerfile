FROM mariadb

COPY ./createdb.sql /
ADD ./createdb.sql /docker-entrypoint-initdb.d
EXPOSE 3306

# RUN mysql
# RUN GRANT ALL PRIVILEGES ON *.* TO 'root'@'%' IDENTIFIED BY 'password';
# RUN ls
# RUN mysql /createdb.sql
