FROM node:16.13.2-alpine3.15

WORKDIR /backend

COPY ./ ./

RUN yarn
RUN yarn build

CMD ["yarn", "start"]