FROM node:12.18.1-alpine

ENV PORT = 3000

WORKDIR /usr/src/app
COPY package*.json ./
RUN npm install --only=production
COPY . .
COPY ./videos ./videos
CMD npm start