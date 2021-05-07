FROM node:12.18.3

RUN mkdir day6
WORKDIR /day6

COPY Server.js /day6/Server.js

RUN npm install express

CMD [ "node", "Server.js" ]

EXPOSE 3000
