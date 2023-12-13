#Set the base image
FROM node:18-alpine
# create the working directory
WORKDIR /usr/app

#copy fiels from the host to WORKDIR
COPY ./package.json ./

#install dependencies for the app
Run npm install

#copy everything else to the container
COPY ./ ./

#start the server 
CMD [ "npm", "start"]
