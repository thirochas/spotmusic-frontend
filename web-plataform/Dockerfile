FROM node:14

WORKDIR /usr/src/app

COPY . .

RUN apt-get update && apt-get install -y wget

RUN npm install

CMD ["node", "server.js"]