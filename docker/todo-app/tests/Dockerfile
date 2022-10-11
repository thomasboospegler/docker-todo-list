FROM mjgargani/puppeteer:trybe1.0

WORKDIR /srv/app

COPY ./e2e ./e2e
COPY ./package-lock.json .
COPY ./package.json .
COPY jest.config.js .
ADD node_modules.tar.gz node_modules

CMD ["npm", "test"]
