FROM node:14

EXPOSE 3001

ADD node_modules.tar.gz .

COPY . .

WORKDIR /todo-app/back-end

CMD ["npm", "start"]
