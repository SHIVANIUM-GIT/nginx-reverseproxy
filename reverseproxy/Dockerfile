#GET the base default nginx image from docker hub
FROM nginx:latest

#Delete the Existing default.conf
RUN rm /etc/nginx/conf.d/default.conf

#Copy the custom default.conf to the nginx configuration
COPY default.conf /etc/nginx/conf.d

COPY index.html /usr/share/nginx/html/index.html