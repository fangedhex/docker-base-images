FROM fangedhex/tinybooter:latest
RUN apt-get update && apt-get install -y --no-install-recommends --no-install-suggests nginx && rm -rf /var/lib/apt/lists/*
ADD nginx.conf /etc/nginx/
ADD nginx.ini /etc/tinybooter.d/
ADD index.html /var/www/
EXPOSE 80
