# Specify a base image
FROM node:alpine

WORKDIR /usr/app

#Install some dependencies
COPY ./package.json  /usr/app
RUN npm install
COPY ./ ./

# Set up a default command
CMD [ "npm","start" ]