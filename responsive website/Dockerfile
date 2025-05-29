# Use nginx as base image
FROM nginx:alpine

# Remove default nginx static files
RUN rm -rf /usr/share/nginx/html/*

# Copy your HTML files into nginx's default directory
COPY . /usr/share/nginx/html

# Expose port 80 (not mandatory but good practice)
EXPOSE 80

