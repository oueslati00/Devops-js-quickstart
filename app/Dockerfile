FROM node:14-alpine
WORKDIR /src
COPY package.json .
RUN yarn install
COPY . .
ENV WDS_SOCKET_PORT=0
ENV CHOKIDAR_USEPOLLING=true
CMD ["yarn","start"]