FROM node:0.10.38

MAINTAINER Germán Podestá <german.podesta@devecoop.com>

RUN npm install -g bower gulp

COPY docker-entrypoint.sh /docker-entrypoint.sh

ENTRYPOINT ["/docker-entrypoint.sh"]
