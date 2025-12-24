FROM node:25.2.1-alpine

WORKDIR /app

COPY package.json package-lock.json .

RUN npm ci

COPY server.js .

CMD ["npm","start"]
