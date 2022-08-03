FROM mjgargani/puppeteer:trybe1.0
WORKDIR /todo-app
EXPOSE 3000
COPY node_modules.tar.gz .
COPY . .
CMD ["npm", "test"]