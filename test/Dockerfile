FROM nginx:latest
COPY ./web/index.html /usr/share/nginx/html/index.html
COPY ./web/style.css /usr/share/nginx/html/style.css
COPY ./web/main.js /usr/share/nginx/html/main.js
COPY --chown=1001:1002 src dst
