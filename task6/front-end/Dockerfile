FROM nginx:latest

# copy front-end files to specified output
COPY ./softy-pinko-front-end /var/www/html/softy-pinko-front-end

# copy nginx conf to container
COPY ./softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf
