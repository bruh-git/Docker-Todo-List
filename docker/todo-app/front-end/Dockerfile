FROM node:14-alpine
EXPOSE 3000
WORKDIR /todo/frontend
ADD ./node_modules.tar.gz ./
USER node
COPY . .
ENTRYPOINT [ "npm","start"]
