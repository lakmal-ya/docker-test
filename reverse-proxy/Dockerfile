# set base image (host OS)
FROM nginx:alpine

# set the working directory in the container
WORKDIR nginx

# copy the content of the local src directory to the working directory
COPY default.conf /etc/nginx/conf.d/

#expose Application port
EXPOSE 80
