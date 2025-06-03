# Use an official PHP runtime as the base image
FROM php:8.2-cli

# Set the working directory inside the container
WORKDIR /app

# Copy all project files into the container
COPY . /app

# Expose a port (Render will pass in PORT dynamically)
EXPOSE 8000

# Start PHP’s built-in server on all network interfaces using Render's PORT variable.
CMD ["php", "-S", "0.0.0.0:8000", "-t", "."]
