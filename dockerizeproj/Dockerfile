FROM node:16.0.0-alpine

WORKDIR /home/chi/Pictures/microarchi
COPY package*.json ./
RUN npm install --only=production
COPY ./src ./src
COPY ./video ./video
CMD npm start