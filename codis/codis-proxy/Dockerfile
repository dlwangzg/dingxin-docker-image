FROM leading/alpine:3.7
MAINTAINER Daliu <liuyg@leadingsoft.com>

WORKDIR /app/codis-proxy

#RUN apk add --no-cache bash

COPY target ./

CMD ["./admin/codis-proxy-admin.sh", "start-foreground"]

EXPOSE 19000
