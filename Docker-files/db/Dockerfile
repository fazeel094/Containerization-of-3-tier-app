FROM mysql:8.0.33

LABEL "Project"="vprofile"
LABEL "Author"="fazeel"

ENV MYSQL_ROOT_PASSWORD="vprodpwd"
ENV MYSQL_DATABASE="accounts"

ADD db_backup.sql /docker-entrypoint-initdb.d/bd_backup.sql