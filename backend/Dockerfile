
# Base Image
FROM node:latest

# Create app directory
WORKDIR /usr/src/app

# Install app dependency
COPY package*.json ./

RUN npm install

# Bundle app source
COPY . .

# Expose the port and start the application
EXPOSE 9000

CMD [ "npm", "run", "dev" ]