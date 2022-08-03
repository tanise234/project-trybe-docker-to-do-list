FROM node:14-alpine
WORKDIR /todo-app
EXPOSE 3000
COPY node_modules.tar.gz .
COPY . .
CMD ["npm", "start"]