# Use Python base image
FROM python:3.9-slim

# Set working directory
WORKDIR /app

# Copy app code
COPY . /app

# Install flask
RUN pip install flask

# Set environment variables (production level)
ENV APP_MODE=production
ENV APP_REGION=canada-west

# Expose port
EXPOSE 8080

# Run the application
CMD ["python", "app.py"]

