FROM node:20-alpine

WORKDIR /app

COPY . .

RUN npm install

EXPOSE 5000

ENTRYPOINT [ "npm", "run", "start"]