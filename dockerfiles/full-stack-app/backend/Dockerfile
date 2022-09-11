# TODO => Instructions for backend
FROM node:alpine

WORKDIR /app

ARG PORT = 5000

ENV PORT=$PORT

EXPOSE $PORT

COPY package*.json .

RUN npm install

COPY . .

CMD ["npm", "run", "dev"]