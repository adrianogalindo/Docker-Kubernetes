#specify a base image
FROM node:alpine

#Directory the container is going to work
WORKDIR /usr/app

#Copy files to the container
COPY ./ ./

#Install some dependencies
RUN npm install

#Default command
CMD ["npm", "start"]