FROM node:15
WORKDIR /usr/node_app
COPY package*.json /usr/node_app
RUN npm install
COPY . /usr/node_app
CMD [ "node", "index.js" ]