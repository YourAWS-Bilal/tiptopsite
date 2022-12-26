FROM nginx:latest
CMD  rm /usr/share/nginx/html/index.html
COPY public /usr/share/nginx/html
COPY nginx/default.conf /etc/nginx/conf.d/default.conf
