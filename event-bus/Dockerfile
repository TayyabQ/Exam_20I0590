FROM node:18-alpine

WORKDIR /3590_event-bus

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 3590

CMD ["npm", "start"]