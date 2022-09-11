# TODO => Instructions for frontend 
FROM node:alpine

WORKDIR /app

ARG PORT = 3000

ENV PORT=$PORT

EXPOSE $PORT

COPY package*.json ./

RUN npm install

COPY . ./

CMD ["npm", "run", "dev"]