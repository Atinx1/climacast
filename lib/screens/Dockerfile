# Use an official Flutter image as the base image
FROM cirrusci/flutter

# Set the working directory inside the container
WORKDIR /app

COPY ../../pubspec.yaml /app/


# Copy the entire project directory into the container at /app


# Install dependencies (geolocator, http, flutter_spinkit)
RUN flutter pub get
COPY . .
# Expose the port the app runs on (if needed)
# EXPOSE 80

# Start the microservice when the container is started
CMD ["sh", "m1.sh"]
