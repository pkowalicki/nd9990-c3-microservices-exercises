FROM node:13.14
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY ./ /app
RUN npm run docker-build
CMD ["node", "./www/server.js"]