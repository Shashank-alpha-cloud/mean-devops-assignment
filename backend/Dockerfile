# Use official Node image
FROM node:18

# Create app directory inside container
WORKDIR /app

# Copy package files
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy all project files
COPY . .

# Expose backend port
EXPOSE 8080

# Start the app
CMD ["npm", "start"]