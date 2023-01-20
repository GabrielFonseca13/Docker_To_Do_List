FROM node:14-alpine

WORKDIR /docker

ADD node_modules.tar.gz .

EXPOSE 3000

COPY . ./docker/todo-app/front-end

ENTRYPOINT [ "npm start" ]