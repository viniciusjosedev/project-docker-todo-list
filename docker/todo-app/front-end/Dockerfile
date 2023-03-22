

FROM node:14-alpine3.17
WORKDIR /app
ADD node_modules.tar.gz .
COPY src ./src
COPY package.json .
COPY .gitignore .
COPY .env .
COPY package-lock.json .
COPY public ./public
EXPOSE 3000
ENTRYPOINT [ "npm" ]
CMD [ "start" ]
