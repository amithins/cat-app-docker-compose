FROM nginx:1.9.1

ADD nginx.conf /etc/nginx/
ADD symfony.conf /etc/nginx/conf.d/
ADD upstream.conf /etc/nginx/conf.d/
RUN rm /etc/nginx/conf.d/default.conf

RUN usermod -u 1000 www-data
