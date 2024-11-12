FROM node:19

WORKDIR /app

COPY package.json .

RUN npm install

EXPOSE 5050

COPY . .

CMD ["npm", "start"]