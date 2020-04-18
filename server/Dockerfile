FROM node:alpine

WORKDIR /app

COPY package.json ./
RUN npm install
COPY . .

CMD ["start", "npm", "start"]