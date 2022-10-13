FROM node:14-alpine
EXPOSE 3001
RUN mkdir -p .
ADD node_modules.tar.gz .
COPY . .
WORKDIR /todo-app/back-end
CMD ["npm", "start"]