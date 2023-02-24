FROM node

WORKDIR /app

COPY . /app

RUN npm config set registry https://registry.npmjs.org

RUN npm install && npm run build

EXPOSE 1234

CMD ["node", "server.js"]

