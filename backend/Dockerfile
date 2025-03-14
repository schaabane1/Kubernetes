# Utilisation d’Amazon Corretto 17
FROM amazoncorretto:17-alpine

# Définir un répertoire de travail
WORKDIR /app

# Copier le fichier JAR du backend
COPY target/paymybuddy.jar .


# Exposer le port de l’application
EXPOSE 8080

# Exécuter l’application
CMD ["java", "-jar", "paymybuddy.jar"]
