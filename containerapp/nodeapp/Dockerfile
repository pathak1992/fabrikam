
FROM node:7
WORKDIR /app
COPY package.json /app
RUN npm start
COPY . /app
CMD node server.js
EXPOSE 8081
