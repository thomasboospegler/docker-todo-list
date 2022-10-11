FROM node:14-alpine

EXPOSE 3000

WORKDIR /todo-app/front-end

COPY ./src ./src
COPY ./public ./public
COPY ./package-lock.json .
COPY ./package.json .
ADD node_modules.tar.gz .

CMD ["npm", "start"]
