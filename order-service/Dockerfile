FROM node:latest
LABEL maintainer="Arnor Erling Einarsson"

ENV NODE_ENV production

COPY . /app
WORKDIR /app
RUN npm install
EXPOSE 80

ENTRYPOINT ["node", "index.js"]