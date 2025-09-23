# Use an official Node.js base image
FROM node:18

# Set working directory
WORKDIR /app

# Copy only necessary files first
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the rest of the app
COPY . .

# Expose the app port
EXPOSE 3000

# Start the application
CMD ["npm", "start"]
