FROM gulp-bower:node-0.10.38-compass

MAINTAINER Germán Podestá <german.podesta@devecoop.com>

RUN mkdir -p /usr/src/app

WORKDIR /usr/src/app

ONBUILD COPY . /usr/src/app
ONBUILD RUN npm install
ONBUILD RUN bower install --allow-root
