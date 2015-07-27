FROM busybox

ADD artifact /var/www/symfony
RUN chown -R 1000:33 /var/www/symfony # www-data:www-data
RUN chmod g+s /var/www/symfony/app/cache
RUN chmod g+s /var/www/symfony/app/logs

VOLUME /var/www/symfony
