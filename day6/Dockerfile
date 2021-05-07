FROM node:12.18.3

RUN mkdir app
WORKDIR /app

COPY Server.js /app/Server.js

RUN npm install express

CMD [ "node", "Server.js" ]

EXPOSE 3000
