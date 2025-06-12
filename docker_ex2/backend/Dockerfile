# Use a minimal Python base image
FROM python:3.8-slim

# Set working directory
WORKDIR /usr/src/app

# Copy everything from current directory into container
COPY . .

# Install Python dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Let Docker know the app listens on port 5000
EXPOSE 5000

# Run the backend app
CMD ["python", "app.py"]
