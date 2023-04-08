
FROM node:14-alpine3.17

RUN mkdir /client

WORKDIR /client

COPY package.json .

RUN npm install

COPY . . 

EXPOSE 3000

CMD ["npm","start"]