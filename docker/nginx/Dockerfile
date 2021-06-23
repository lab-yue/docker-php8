FROM nginx:1.19.7-alpine

WORKDIR /home/app

ENV TZ=Asia/Tokyo

RUN apk add --update --no-cache tzdata

COPY ./nginx.conf /etc/nginx/conf.d/default.conf
