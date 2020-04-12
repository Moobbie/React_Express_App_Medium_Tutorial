# Dockerfile for api

# Stage 1: Server
FROM node:10.16-alpine

# Working directory be app
WORKDIR /api

COPY package*.json ./

# Install dependencies
RUN npm install

# copy local files to app folder
COPY . .

EXPOSE 80

CMD ["npm","start"]