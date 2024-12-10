# Using an official NGINX image from the Docker Hub
FROM nginx:latest

# Copy the HTML file into the NGINX server's default directory
COPY index.html /usr/share/nginx/html/

# Expose port 80 to access the web application
EXPOSE 80

# Start NGINX in the foreground (default behavior of NGINX)
CMD ["nginx", "-g", "daemon off;"]
