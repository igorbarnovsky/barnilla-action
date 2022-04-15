FROM nginx:latest

RUN rm -vf /etc/nginx/nginx.conf

COPY nginx.conf /etc/nginx/
COPY index.html /usr/share/nginx/html/index.html
EXPOSE 80
