
FROM node:14-alpine3.17
WORKDIR /app
ADD node_modules.tar.gz .
COPY src ./src
COPY package.json .
COPY .gitignore .
COPY .env .
COPY package-lock.json .
EXPOSE 3001
ENTRYPOINT [ "npm" ]
CMD [ "start" ]
