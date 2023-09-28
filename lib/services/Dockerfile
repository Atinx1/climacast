# Use an official Flutter image as the base image
FROM cirrusci/flutter

# Set the working directory inside the container
WORKDIR /app

# Copy the entire project directory into the container at /app
COPY . .

# Install dependencies (geolocator, http, flutter_spinkit)


# Expose the port the app runs on (if needed)
# EXPOSE 80

# Start the microservice when the container is started
CMD ["sh", "m2.sh"]
