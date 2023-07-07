# Specify the parent image from which we build
FROM ubuntu:latest

# Set the working directory
WORKDIR /app

# Copy files from your host to your current working directory
COPY . /app/.

# Webserver will listen on this port
EXPOSE 8080/tcp

# Run the application
CMD ["/app/writefreely"]