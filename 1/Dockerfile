FROM nginx
COPY site.*.conf /etc/nginx/conf.d/
RUN rm /etc/nginx/conf.d/default.conf \
    && mkdir /usr/share/nginx/site_one \
    && mkdir /usr/share/nginx/site_one/pages \
    && mkdir /usr/share/nginx/site_one/logs \
    && mkdir /usr/share/nginx/site_two \
    && mkdir /usr/share/nginx/site_two/pages \
    && mkdir /usr/share/nginx/site_two/logs 
EXPOSE 80/tcp
EXPOSE 3000/tcp

