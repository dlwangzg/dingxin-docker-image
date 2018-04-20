FROM leading/alpine:3.7
MAINTAINER Daliu <liuyg@leadingsoft.com>

WORKDIR /app/codis-server

#RUN apk add --no-cache bash

COPY target ./

CMD ["./admin/codis-server-admin.sh", "start-foreground"]

EXPOSE 6379
