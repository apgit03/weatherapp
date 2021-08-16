FROM node:latest

RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app
RUN npm install

COPY package*.json ./

COPY . .

CMD [ "npm", "run", "dev" ]
