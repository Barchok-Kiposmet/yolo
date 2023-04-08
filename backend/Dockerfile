FROM node:13.12.0-alpine as backend

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 5001

CMD [ "npm", "start" ]