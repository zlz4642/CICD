FROM     ubuntu:20.04
RUN      apt-get update && \
         apt-get install -y apache2
COPY     Web_Sample /var/www/html
EXPOSE   80
CMD     ["/usr/sbin/apache2ctl","-DFOREGROUND"]
