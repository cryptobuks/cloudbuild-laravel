FROM nginx:1.16.0-alpine

RUN rm /etc/nginx/conf.d/default.conf
RUN apk add --no-cache openssl bash

COPY ./nginx.conf /etc/nginx/conf.d
