FROM node

COPY . /app

WORKDIR /app

RUN npm config set registry https://registry.npmjs.org

RUN npm install

EXPOSE 3000

CMD ["npm", "start"]