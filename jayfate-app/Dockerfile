FROM node:lts

WORKDIR /jayfate-app
COPY package.json .
RUN npm install
COPY . .
CMD npm start
