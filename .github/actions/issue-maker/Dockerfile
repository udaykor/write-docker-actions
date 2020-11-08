FROM node:slim

COPY package*.json ./

RUN apt-get update && apt-get install -y yarn && yarn

COPY . .

CMD [ "node", "/src/index.js" ]
