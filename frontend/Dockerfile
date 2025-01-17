# Gebruik een specifieke versie van nginx:alpine
FROM nginx:alpine

# Verwijder bestaande bestanden in de Nginx HTML map
RUN rm /usr/share/nginx/html/*

# Kopieer het nginx.conf bestand naar de container
COPY nginx.conf /etc/nginx/nginx.conf


# Kopieer je aangepaste index.html naar de container
COPY ./index.html /usr/share/nginx/html/index.html

# Expose poort 80
EXPOSE 80
EXPOSE 443