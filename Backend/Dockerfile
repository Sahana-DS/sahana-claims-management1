# Use the official Node.js image
FROM node:18

# Set the working directory
WORKDIR /app

# Copy package files and install dependencies
COPY package*.json ./
RUN npm install

# Copy application code
COPY . .

# Expose the app's port
EXPOSE 3000

# Start the server
CMD ["node", "server.js"]
