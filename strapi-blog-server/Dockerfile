FROM node:14.17

WORKDIR /usr/src/app

ENV PATH /usr/src/app/node_modules/.bin:$PATH

COPY package.json .

RUN npm install

COPY . .
