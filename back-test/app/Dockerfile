FROM node:16-alpine as builder

COPY package*.json .
RUN npm install
COPY . .
EXPOSE 3000
CMD ["node", "index.js"] 
