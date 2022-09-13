FROM node:10-alpine

WORKDIR /

COPY . .


RUN npm install

EXPOSE 3001

CMD [ "node", "server.js" ]