# Use the official Python image
FROM python:3.10-slim

# Set the working directory
WORKDIR /

# Copy the requirements file and install dependencies
COPY requirements.txt requirements.txt
RUN pip install --no-cache-dir -r requirements.txt

# Copy the application code
COPY . .

# Expose the port that the app runs on
EXPOSE 8080

# Command to run the application
CMD ["python", "app.py"]
