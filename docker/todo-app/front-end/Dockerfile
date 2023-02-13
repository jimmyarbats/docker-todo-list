FROM node:14

EXPOSE 3000

ADD node_modules.tar.gz .

COPY . .

WORKDIR /todo-app/front-end

CMD ["npm", "start"]
