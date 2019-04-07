FROM wordpress:php7.3-fpm-alpine
MAINTAINER Sonny Yu <sonnyyuirm@gmail.com>
RUN  apk add --upgrade --no-cache tzdata \
     && rm -rf /var/cache/apk/* /tmp/*
ENV  TZ=America/Los_Angeles
COPY ./scripts/wait-for /usr/local/bin/wait-for
RUN chmod a+x /usr/local/bin/wait-for

