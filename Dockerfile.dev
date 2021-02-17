FROM node:15.8-alpine3.13

WORKDIR /app

COPY package.json .
RUN npm install

COPY --chown=node:node . .

CMD ["npm", "run", "start"]