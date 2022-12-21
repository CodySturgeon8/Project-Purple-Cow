FROM node:16.16.0

WORKDIR /app

COPY ["package.json", "package-lock.json", "./"]

RUN ls
RUN npm install

COPY . .

EXPOSE 5000

CMD ["node", "server.js"]