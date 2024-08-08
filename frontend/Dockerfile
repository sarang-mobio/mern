# Start from a Node LTS version
FROM node:16

# Create app directory
WORKDIR /app

# Install app dependencies
COPY ./package*.json ./

# Install dependencies
RUN npm install

# Copy app source code
COPY . .

# Expose port and start application
EXPOSE 3000

# Start the app
CMD ["npm", "run", "start"]