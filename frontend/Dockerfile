FROM node:latest

WORKDIR /usr/app

COPY package*.json ./

COPY . .

RUN npm install

EXPOSE 3001

CMD ["npm", "start"]