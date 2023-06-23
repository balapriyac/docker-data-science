# Use the official Python image as the base image
FROM python:3.9-slim

# Set the working directory in the container
WORKDIR /app

# Copy the requirements.txt file to the container
COPY requirements.txt .

# Install the dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Copy the script file to the container
COPY house_price_prediction.py .

# Set the command to run your Python script
CMD ["python", "house_price_prediction.py"]
