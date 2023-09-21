# specify a base image
FROM node:14-alpine

WORKDIR /usr/app

# install files index.js etc. and dependencies
COPY ./package.json ./
RUN npm install

# copy rest of files except package.json already copied in previous step. avoid a full rebuild process
COPY ./ ./

# default command
CMD ["npm","start"]
