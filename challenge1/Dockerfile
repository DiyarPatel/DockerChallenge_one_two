# Use the official Nginx image from Docker Hub
FROM nginx:alpine

# Copy the contents of the public folder to the Nginx HTML directory
COPY public /nginx/html

# Expose port 8080
EXPOSE 8080

# Start Nginx when the container starts
CMD ["nginx", "-g", "daemon off;"]
