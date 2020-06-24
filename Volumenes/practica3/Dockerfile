FROM debian

RUN \
     apt-get update && \
     apt-get -y install apache2 	\
     			 php 	 	\
     			 php-cli 	\
     			 php-common

COPY index.php /var/www/html/index.php

CMD ["/usr/sbin/apache2ctl", "-DFOREGROUND"]


