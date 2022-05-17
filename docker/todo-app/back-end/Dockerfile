FROM node:14-alpine
EXPOSE 3001
COPY . /app
RUN chown -R node:node /app
USER node
CMD npm start
