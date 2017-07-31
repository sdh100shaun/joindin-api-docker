FROM alpine

RUN apk update  && \
apk add git

RUN git clone https://github.com/joindin/joindin-api.git /srv

RUN mv /srv/src/config.php.dist /srv/src/config.php
RUN mv /srv/src/database.php.dist /srv/src/database.php

VOLUME /srv

	
