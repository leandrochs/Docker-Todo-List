# syntax=docker/dockerfile:1

FROM node:14-alpine

WORKDIR /frontend-app

COPY . .

ADD node_modules.tar.gz .

EXPOSE 3000

CMD [ "npm", "start" ]
