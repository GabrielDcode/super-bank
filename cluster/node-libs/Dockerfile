# Dockerfile
FROM node:22-alpine

# Set working directory for the shared libraries
WORKDIR /usr/src/app

# Copy over the package.json files from each service
COPY package.json .
COPY package-lock.json .

# Install all dependencies into node_modules
RUN npm install