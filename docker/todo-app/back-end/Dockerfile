FROM node:14-alpine
WORKDIR /todo/backend
EXPOSE 3001
ADD ./node_modules.tar.gz ./
USER node
COPY . .
ENTRYPOINT [ "npm","start"]
