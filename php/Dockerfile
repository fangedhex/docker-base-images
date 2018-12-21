FROM fangedhex/base-images:nginx
RUN apt-get update \
&& apt-get install -y --no-install-recommends --no-install-suggests git php-fpm php-ctype php-iconv php-tokenizer php-xml php-simplexml php-mbstring php-dom php-gd php-pdo php-mysql php-zip composer \
&& rm -rf /var/lib/apt/lists/*
ADD etc /etc/
ADD index.php /var/www/
