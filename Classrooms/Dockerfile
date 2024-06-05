FROM node:18-alpine

WORKDIR /1590_classrooms

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 1590

CMD ["npm", "start"]