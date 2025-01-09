# Use a lightweight web server image
FROM nginx:alpine

# Copy the HTML, CSS, and JS files into the web server's root directory
COPY index.html /usr/share/nginx/html/
COPY styles.css /usr/share/nginx/html/
COPY script.js /usr/share/nginx/html/

# Expose port 80 for the web server
EXPOSE 80

# Start the web server
CMD ["nginx", "-g", "daemon off;"]