# Use the official Node.js image as base
FROM node:20

# Set the working directory in the container
WORKDIR /backend

# Copy package.json and package-lock.json to the working directory
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the rest of the application code
COPY . .

# Expose port 8000
EXPOSE 8000

# Command to run the application
CMD ["node", "server.js"]
