FROM fangedhex/tinybooter
RUN apt-get update && apt-get install -y --no-install-recommends --no-install-suggests curl \
&& curl -sL https://deb.nodesource.com/setup_10.x | bash - \
&& apt-get install -y nodejs
ADD etc /etc/
