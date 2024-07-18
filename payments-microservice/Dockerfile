FROM node:18-alpine as builder

ENV NODE_ENV build

# USER node
WORKDIR /usr/src/app

COPY package-lock.json ./
COPY package.json ./


RUN npm install
COPY . .