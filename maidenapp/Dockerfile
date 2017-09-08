# MAINTAINER: Ajay Kumar Mahto <ajay.mahto@paytmmall.com>

# Use official python-runtime as parent image
FROM python:2.7-slim

# Setting working dir [/app]
WORKDIR /app

# Copy current directory contents to working directory.
ADD . /app

# Install dependencies using pip
RUN pip install -r requirements.txt

# Expose port 80
EXPOSE 80

# Define Environment Variables.
ENV NAME World

# Run app.py when the container launches.
CMD ["python", "app.py"]
