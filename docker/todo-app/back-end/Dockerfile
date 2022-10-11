FROM node:14-alpine

EXPOSE 3001

WORKDIR /todo-app/back-end

COPY ./src ./src
COPY ./package-lock.json .
COPY ./package.json .
ADD node_modules.tar.gz .

CMD ["npm", "start"]
