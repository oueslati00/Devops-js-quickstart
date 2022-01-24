FROM node:14-alpine
WORKDIR /src
COPY package.json .
RUN npm install
COPY . .
CMD ["npm","start"]