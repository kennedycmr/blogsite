# Specify the parent image from which we build
#FROM nginx:latest
#FROM ubuntu:latest
FROM ubuntu:latest

# Set the working directory
WORKDIR /

# Copy files from your host to your current working directory
COPY . .

# Webserver will listen on this port
EXPOSE 8080/tcp

# Run the application
CMD ["writefreely"]