FROM wordpress:5.7

RUN apt-get update && apt-get install -y mariadb-client

ENV WORDPRESS_DB_HOST="db:3306"
ENV WORDPRESS_DB_USER="wpuser"
ENV WORDPRESS_DB_PASSWORD="96c89d0c"
ENV WORDPRESS_DB_NAME="wordpress"

LABEL description="Mysql para wordpress"

VOLUME /var/www/html/
EXPOSE 80