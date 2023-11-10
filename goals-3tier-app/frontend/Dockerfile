FROM node:14

WORKDIR /app

COPY package.json .

RUN npm install

COPY . . 

ARG PORT_NUMBER 3000

EXPOSE $PORT_NUMBER

CMD ["npm", "start"]