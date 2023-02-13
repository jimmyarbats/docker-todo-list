FROM node:14-alpine

EXPOSE 3000

ADD node_modules.tar.gz .

WORKDIR /todo-app/front-end

COPY . .

CMD ["npm", "start"]
