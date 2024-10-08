# Use a base Python image from the Microsoft container registry
FROM mcr.microsoft.com/devcontainers/python:3

# Install any OS-level packages
RUN apt-get update && apt-get install -y \
    libpq-dev build-essential

# Install Python packages (optional)
# You can leave this for pip to handle via requirements.txt in the postCreateCommand
# RUN pip install <your-package>

# Set up any other environment configurations
