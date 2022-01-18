FROM node:lts-alpine
RUN mkdir /app-front
WORKDIR /app-front
COPY package*.json ./
COPY public ./
RUN npm i

CMD npm start