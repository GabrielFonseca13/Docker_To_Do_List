FROM node:14-alpine

WORKDIR /docker

ADD node_modules.tar.gz .

EXPOSE 3001

COPY . ./docker/todo-app/back-end

ENTRYPOINT [ "npm start" ]