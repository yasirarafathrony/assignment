
# Get the base node image
FROM node:latest

RUN mkdir /usr/src/app
COPY . /usr/src/app
WORKDIR /usr/src/app

RUN npm install

CMD ["npm", "start"]