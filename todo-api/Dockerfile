FROM node:8.1.2

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install

COPY ./ ./

ENV API_PORT=6000

EXPOSE 6000

CMD ["npm","run","start"]
