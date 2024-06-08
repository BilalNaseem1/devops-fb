# Use the official Nginx image from the Docker Hub
FROM nginx:latest

# Copy custom configuration file from the current directory
# into the container
COPY nginx.conf /etc/nginx/nginx.conf

# Copy your static files to the default Nginx public directory
COPY index.html /usr/share/nginx/html