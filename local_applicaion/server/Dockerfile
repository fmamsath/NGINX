# Create a new Dockerfile
FROM node:14

# Set the working directory
WORKDIR /app

# Copy the package.json file
COPY package*.json ./

# Install the dependencies
RUN npm install

# Copy the application code
COPY . .

# Expose the port
EXPOSE 7777

# Run the command to start the server
CMD ["npm", "run", "start"]