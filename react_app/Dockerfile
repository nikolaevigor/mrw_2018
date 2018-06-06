FROM node:alpine

RUN mkdir /app
WORKDIR /app

COPY package.json /app
COPY yarn.lock /app
RUN yarn install
COPY public /app/public
COPY src /app/src

CMD yarn start