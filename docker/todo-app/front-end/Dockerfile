FROM node:14-alpine
WORKDIR /todo/frontend
ADD ./node_modules.tar.gz ./
USER node
COPY . .
EXPOSE 3000
ENTRYPOINT [ "npm","start"]
