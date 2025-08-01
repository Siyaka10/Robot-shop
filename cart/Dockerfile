FROM node:14

WORKDIR /app   

COPY package*.json ./

ENV INSTANA_AUTO_PROFILE=true

RUN npm install

COPY . .

EXPOSE 8080

CMD ["node", "server.js"]