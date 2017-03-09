FROM ubuntu

RUN apt-get update && apt-get install -y \
	apache2

RUN a2enmod rewrite
	
	
RUN usermod -u 1000 www-data

CMD /usr/sbin/apache2ct1 -D FOREGROUND

EXPOSE 80
EXPOSE 443
