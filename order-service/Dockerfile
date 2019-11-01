FROM node:latest
LABEL maintainer="Arnor Erling Einarsson & Emil Newel & Magnús Freyr Sveinsson"

ENV NODE_ENV production
ENV PORT 80

COPY . /app
WORKDIR /app
RUN npm install


ENTRYPOINT ["node", "index.js"]