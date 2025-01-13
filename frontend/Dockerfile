# Gebruik een specifieke versie van nginx:alpine
FROM nginx:alpine3.16

# Verwijder bestaande bestanden in de Nginx HTML map
RUN rm /usr/share/nginx/html/*

# Kopieer je aangepaste index.html naar de container
COPY ./index.html /usr/share/nginx/html/index.html

# Expose poort 80
EXPOSE 80