FROM node:14-alpine
WORKDIR /todo/frontend
EXPOSE 3000
ADD ./node_modules.tar.gz ./
USER node
COPY . .
ENTRYPOINT [ "npm","start"]
