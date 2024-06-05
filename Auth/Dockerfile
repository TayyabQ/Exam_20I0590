FROM node:18-alpine

WORKDIR /0590_auth

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 0590

CMD ["npm", "start"]