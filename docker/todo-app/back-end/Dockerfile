FROM node:14-alpine

EXPOSE 3001

WORKDIR /todo-app/back-end

ADD node_modules.tar.gz .
COPY ./src ./src
COPY package-lock.json .
COPY package.json .

CMD ["npm", "start"]
