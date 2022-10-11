FROM mjgargani/puppeteer:trybe1.0

WORKDIR /todo-app/tests

COPY ./e2e ./e2e
COPY ./package-lock.json .
COPY ./package.json .
COPY jest.config.js .
ADD node_modules.tar.gz .

CMD ["npm", "test"]
