FROM node:18-alpine

WORKDIR /4590_post

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 4590

CMD ["npm", "start"]