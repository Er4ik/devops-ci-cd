FROM node:17-alpine3.14

WORKDIR /app

COPY package.json .

RUN npm install

COPY . /app

EXPOSE 80

CMD [ "npm", "start" ]