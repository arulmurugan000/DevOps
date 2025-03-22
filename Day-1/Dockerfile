# Use the official Nginx image
FROM nginx:latest

# Copy the custom HTML file into Nginx's default directory
COPY index.html /usr/share/nginx/html/index.html

# Expose port 80 for web access
EXPOSE 80

# Start Nginx in the foreground
CMD ["nginx", "-g", "daemon off;"]
