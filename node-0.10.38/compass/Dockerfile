FROM devecoop/gulp-bower:node-0.10.38

MAINTAINER Germán Podestá <german.podesta@devecoop.com>

RUN apt-get update && \
    apt-get install -y git git-core wget zip zlib1g-dev ruby ruby-dev fontforge eot-utils ttfautohint build-essential

RUN gem install bootstrap-sass
RUN gem install compass
