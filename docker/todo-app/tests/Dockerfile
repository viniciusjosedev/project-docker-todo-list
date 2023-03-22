

FROM mjgargani/puppeteer:trybe1.0
WORKDIR /app
ADD node_modules.tar.gz .
COPY e2e ./e2e
COPY jest.config.js .
COPY package.json .
COPY package-lock.json .
EXPOSE 3000
ENTRYPOINT [ "npm" ]
CMD [ "test" ]

