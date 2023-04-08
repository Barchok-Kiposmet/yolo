
FROM node:13.12.0 as build

WORKDIR /app

COPY  . .

RUN npm install

FROM node:alpine as main

COPY --from=build /app /

EXPOSE 3000

CMD [ "npm", "start" ]