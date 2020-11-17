FROM node:slim

COPY package*.json ./

RUN npm install -g npm@7.0.11

COPY . .

CMD [ "node", "/src/index.js" ]
