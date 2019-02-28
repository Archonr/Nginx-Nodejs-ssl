# Set nginx base image
FROM nginx

# File Author / Maintainer
#MAINTAINER Adrien Desbiaux

#COPY docker-entrypoint.sh /
#ENTRYPOINT ["/docker-entrypoint.sh"]

# Copy custom configuration file from the current directory
COPY nginx.conf /etc/nginx/nginx.conf
#CMD [ “nginx”, “-g”, “daemon off;”]
#VOLUME ["/etc/nginx/ssl", "/etc/nginx/psw"]

# Append "daemon off;" to the beginning of the configuration
# in order to avoid an exit of the container
#RUN echo "daemon off;" >> /etc/nginx/nginx.conf

# Expose ports
#EXPOSE 80

# Define default command
#CMD service nginx start
