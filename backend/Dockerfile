FROM mongo-express:latest

RUN mkdir /app

WORKDIR /app

COPY packages*.jason .

RUN npm install

COPY . .

CMD ["npm", "start"]