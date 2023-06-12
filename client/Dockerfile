FROM node:18.16.0-alpine

WORKDIR /app

RUN npm install -g npm@9.7.1

COPY package*.json .

RUN npm install --no-scripts

COPY . .

EXPOSE 3000

CMD ["npm", "run", "serve"]