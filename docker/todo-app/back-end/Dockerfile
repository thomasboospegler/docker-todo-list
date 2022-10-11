FROM node:14-alpine

EXPOSE 3001

WORKDIR /srv/app

COPY ./src ./src
COPY ./package-lock.json .
COPY ./package.json .
ADD node_modules.tar.gz node_modules

CMD ["npm", "start"]
