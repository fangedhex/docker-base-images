FROM fangedhex/base-images:nginx
RUN apt-get update && apt-get install -y --no-install-recommends --no-install-suggests php-fpm php-ctype php-iconv php-tokenizer php-xml php-simplexml php-mbstring php-dom php-gd php-pdo composer && rm -rf /var/lib/apt/lists/*
ADD php-fpm.conf /etc/php/7.3/fpm/
ADD loc/* /etc/nginx/loc/
ADD index.php /var/www/
ADD tinybooter.d/* /etc/tinybooter.d/
