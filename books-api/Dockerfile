FROM node:14

WORKDIR /books-api
COPY package.json .
RUN npm install
COPY . .
CMD npm start
