ARG MYSQL_VERSION=8.4

FROM mysql:${MYSQL_VERSION}

# Dump de la db (structure + données) exécuté si le volume de données est vide
COPY ./mysql-docker/initdb/ /docker-entrypoint-initdb.d/

 
EXPOSE 3306



