#Builder
FROM node:20-alpine AS builder
WORKDIR /usr/src/app
COPY package*.json ./
RUN npm install
COPY . .
CMD ["node", "index.js"]

#Runner
#FROM builder
#WORKDIR /usr/src/app
#CMD ["node", "index.js"]