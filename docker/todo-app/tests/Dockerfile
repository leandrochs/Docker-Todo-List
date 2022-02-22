# syntax=docker/dockerfile:1

FROM mjgargani/puppeteer:trybe1.0

WORKDIR /tests-app

COPY . .

ADD node_modules.tar.gz .

CMD [ "npm", "test" ]
