FROM node:14-alpine
EXPOSE 3001
WORKDIR /todo/backend
ADD ./node_modules.tar.gz ./
USER node
COPY . .
ENTRYPOINT [ "npm","start"]
