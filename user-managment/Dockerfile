# Use an official Node runtime
FROM node:18

# Set working directory
WORKDIR /app

# Copy package files and install dependencies
COPY package*.json ./
RUN npm install

# Copy all remaining files
COPY . .

# Expose the port
EXPOSE 5000

# Start the server
CMD ["node", "server.js"]
