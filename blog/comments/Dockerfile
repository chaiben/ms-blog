# Specify a base image
FROM node:14-alpine

WORKDIR /usr/app

# Install dependencies
COPY ./package.json ./
RUN npm install
COPY ./ ./

# Start the application
CMD ["npm", "start"]