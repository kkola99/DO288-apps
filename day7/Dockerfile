FROM node:12.18.3

RUN mkdir day7/node
WORKDIR /day7/node

COPY server.js /day7/node/server.js

RUN npm install express

CMD [ "node", "server.js" ]

EXPOSE 3000
