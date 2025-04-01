# Verwenden Sie ein Basisimage mit PostgreSQL
FROM postgres:latest

# Setzen Sie Umgebungsvariablen
ENV POSTGRES_USER=youruser
ENV POSTGRES_PASSWORD=yourpassword
ENV POSTGRES_DB=yourdatabase

# Installieren Sie das PostgreSQL-Client-Tool
RUN apt-get update && apt-get install -y postgresql-client

# Öffnen Sie den PostgreSQL-Port
EXPOSE 5432
