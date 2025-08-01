FROM node:14

WORKDIR /usr/src/app

ENV INSTANA_AUTO_PROFILE true
COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 8080

CMD [ "node", "server.js" ]