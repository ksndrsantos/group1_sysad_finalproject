# Use the official Nginx image from Docker Hub
FROM nginx:latest

# Copy index.html into Nginx default directory
COPY ./index.html /usr/share/nginx/html/index.html

# Expose port 80 for access
EXPOSE 80

# Run Nginx in the foregroundd
CMD ["nginx", "-g", "daemon off;"]
