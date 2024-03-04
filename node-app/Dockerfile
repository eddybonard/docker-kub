FROM node:20

WORKDIR /node-app

COPY package.json /node-app/

RUN npm install 

COPY . /node-app/

EXPOSE 80

CMD [ "node", "server.js" ]