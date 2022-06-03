FROM mysql:5.7

RUN apt-get update && apt-get install -y mariadb-client

ENV MYSQL_DATABASE="wordpress"
ENV MYSQL_USER="wpuser"
ENV MYSQL_PASSWORD="96c89d0c" 
ENV MYSQL_RANDOM_ROOT_PASSWORD="1" 

LABEL description="Mysql para wordpress"
