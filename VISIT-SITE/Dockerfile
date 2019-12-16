#specify a base image
FROM node:alpine

#Directory the container is going to work
WORKDIR /app

#Copy files to the container but wont change if change just other files in COPY/. /.
COPY ./package.json ./

#Install some dependencies
RUN npm install
COPY ./ ./

#Default command
CMD ["npm", "start"]