# syntax=docker/dockerfile:1

FROM mjgargani/puppeteer:trybe1.0

WORKDIR /tests-app

COPY . .

ADD node_modules.tar.gz .

EXPOSE 3000

CMD [ "npm", "test" ]
