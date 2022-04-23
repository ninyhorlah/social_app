FROM node:18.0-alpine3.14

WORKDIR /social_app_client

COPY package.json yarn.lock ./

RUN yarn install

COPY . .

EXPOSE 3000

CMD ["yarn", "start"]