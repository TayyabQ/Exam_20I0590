FROM node:18-alpine

WORKDIR /2590_client

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 2590

CMD ["npm", "start"]