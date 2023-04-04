
FROM node:gallium-bullseye-slim

RUN mkdir /client

WORKDIR /client

COPY . .

RUN npm install

EXPOSE 3000

CMD ["npm","start"]