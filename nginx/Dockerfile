FROM nginx:1.17.10-alpine
LABEL maintainer=MasanoriIwakura

RUN apk add --no-cache nginx-module-image-filter

COPY ./conf/nginx.conf /etc/nginx/
COPY ./conf/default.conf /etc/nginx/conf.d/
