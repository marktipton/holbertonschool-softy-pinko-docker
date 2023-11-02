# Latest version of Nginx
FROM nginx:latest

# Remove Nginx configuration file'
RUN rm /etc/nginx/conf.d/default.conf

COPY softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf

COPY softy-pinko-front-end /var/www/html/softy-pinko-front-end

EXPOSE 9000

CMD ["nginx", "-g", "daemon off;"]