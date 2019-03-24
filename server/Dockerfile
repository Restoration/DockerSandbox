# Get Node.js latest version from official
FROM node:latest

# Set the working directory to /app
WORKDIR /app

# Copy the current directory contents into the container at /app
COPY . /app

# Install any needed packages specified in package.jsom
RUN npm install

# Make port 80 available to the world outside this container
EXPOSE 8080

# Define environment variable
#ENV NAME World

# Run app.py when the container launches
CMD ["npm", "start"]
