# Use a base Node.js image
FROM node:latest

# Set a working directory
WORKDIR /app

# Install npm utilities globally
RUN npm install -g npm-check npm-run-all

# Set default command or entrypoint (optional)
CMD ["npm", "help", "npx"]