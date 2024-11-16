# Use Python base image
FROM python:3.9-slim

# Install dependencies
RUN pip install --no-cache-dir torch torchvision==0.20.0

# Copy code files to the container
COPY . /app

# Set working directory
WORKDIR /app

# Default command to run the script
CMD ["python", "main.py"]
