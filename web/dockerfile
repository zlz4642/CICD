FROM     ubuntu:20.04
ENV      DEBIAN_FRONTEND noninteractive
RUN      apt-get update && \
         apt-get install php -y && \
         apt-get install -y apache2
COPY     Web_Sample /var/www/html
EXPOSE   80
CMD     ["/usr/sbin/apache2ctl","-DFOREGROUND"]
