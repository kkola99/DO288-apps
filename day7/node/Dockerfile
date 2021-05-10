FROM node:12.18.3

RUN mkdir node
WORKDIR /node

COPY server.js /node/server.js

RUN npm install express

CMD [ "node", "server.js" ]

EXPOSE 3000
