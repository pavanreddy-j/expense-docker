FROM nginx
RUN rm -rf /usr/share/nginx/html/index.html
RUN rm -rf /etc/nginx/nginx.config
COPY nginx.conf /etc/nginx/nginx.config
COPY code/usr/share/nginx/html/