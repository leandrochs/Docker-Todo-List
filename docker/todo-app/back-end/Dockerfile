# syntax=docker/dockerfile:1

FROM node:14-alpine

WORKDIR /backend-app

COPY . .

ADD node_modules.tar.gz .

EXPOSE 3001

CMD [ "npm", "start" ]
