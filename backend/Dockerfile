#syntax=docker/dockerfile:1

FROM node:lts-alpine3.14

WORKDIR /usr/src/app

COPY ["package.json", "package-lock.json*", "./"]

RUN npm install

COPY . .

CMD [ "node", "index.js" ]

EXPOSE 3000
