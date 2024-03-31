# Use an official nginx image as a parent image
FROM nginx:alpine

# Set the working directory in the container
WORKDIR /usr/share/nginx/html

# Copy the current directory contents into the container at /usr/share/nginx/html
COPY . .

# Inform Docker that the container is listening on port 80 at runtime.
EXPOSE 80

# Start nginx and keep it running in the foreground
CMD ["nginx", "-g", "daemon off;"]
