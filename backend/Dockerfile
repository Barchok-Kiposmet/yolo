FROM node:13.12.0-alpine as backend

WORKDIR /backend

COPY package.json .

RUN npm install

COPY . /backend

EXPOSE 5001

CMD [ "npm", "start" ]