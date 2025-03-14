FROM mysql:8

# Définir les variables d’environnement
ENV MYSQL_ROOT_PASSWORD=password
ENV MYSQL_DATABASE=db_paymybuddy
ENV MYSQL_USER=paymybuddy
ENV MYSQL_PASSWORD=paymybuddy

# Copier les scripts de création de la base
COPY initdb /docker-entrypoint-initdb.d/
