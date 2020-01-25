#FROM node:10.16.0-alpine
FROM node:12-alpine
RUN apk update && apk add --virtual build-dependencies build-base gcc wget git python2

WORKDIR /usr/src/app
ENTRYPOINT npm install && npm run start
