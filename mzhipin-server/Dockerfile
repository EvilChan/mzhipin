FROM node:12.18.4-alpine3.9
WORKDIR /usr/src/app
COPY ./ /usr/src/app
RUN npm install --registry=https://registry.npm.taobao.org
USER node
EXPOSE 4000