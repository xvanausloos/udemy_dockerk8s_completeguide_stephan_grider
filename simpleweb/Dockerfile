# specify a base image
FROM node:14-alpine

# install files index.js etc. and dependencies
COPY ./ ./
RUN npm install



# default command
CMD ["npm","start"]
