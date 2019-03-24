# Get Node.js latest version from official
FROM node:latest

# Define environment variable
ENV PORT=8080

# Author name
LABEL author="Ryota"

# Set the working directory to /app
WORKDIR /app

# Copy package.json from app directory to the current direcotry
COPY package.json /app

# Install any needed packages specified in package.jsom
RUN npm install

# Copy the current directory contents into the container at /app
COPY . /app

# Make port 80 available to the world outside this container
EXPOSE $PORT

# Run app.py when the container launches
CMD node server.js


