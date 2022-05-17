FROM mjgargani/puppeteer:trybe1.0
WORKDIR /todo/test
ADD ./node_modules.tar.gz ./
USER node
COPY . .
ENTRYPOINT [ "npm","start"]
