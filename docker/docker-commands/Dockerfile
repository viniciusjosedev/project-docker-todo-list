
FROM node:14
ADD node_modules.tar.gz /home/node
COPY src /home/node/src
COPY package.json /home/node
COPY .gitignore /home/node
COPY .env /home/node
COPY package-lock.json /home/node
WORKDIR /home/node/
ENTRYPOINT [ "npm" ]
CMD [ "start" ]
