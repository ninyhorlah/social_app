FROM node:18.0-alpine3.14

WORKDIR /social_app_server

COPY package.json yarn.lock ./

RUN yarn install

COPY . .

EXPOSE 8800

CMD ["yarn", "start"]