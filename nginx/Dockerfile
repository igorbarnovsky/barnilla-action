FROM nginx

RUN rm -vf /etc/nginx/nginx.conf

COPY nginx.conf /etc/nginx/
	 index.html /var/www/html/

COPY entrypoint.sh /entrypoint.sh
RUN  chmod +x /entrypoint.sh

ENTRYPOINT ["/entrypoint.sh"]