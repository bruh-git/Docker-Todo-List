FROM mjgargani/puppeteer:trybe1.0
WORKDIR /todo/tests
ADD ./node_modules.tar.gz ./
USER node
COPY . .
ENTRYPOINT [ "npm","start"]
