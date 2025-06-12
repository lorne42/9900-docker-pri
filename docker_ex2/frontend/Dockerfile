# Use Node.js base image
FROM node:14

# Set working directory
WORKDIR /usr/src/app

# Copy frontend source code
COPY . .

# Install Node.js dependencies
RUN yarn install

# Expose the default port (optional since docker-compose handles this)
EXPOSE 3000

# Run the frontend
CMD ["yarn", "start"]
