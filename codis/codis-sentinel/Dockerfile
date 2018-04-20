FROM leading/alpine:3.7
MAINTAINER Daliu <liuyg@leadingsoft.com>

WORKDIR /app/codis-sentinel

#RUN apk add --no-cache bash

COPY target ./

CMD ["./admin/codis-sentinel-admin.sh", "start-foreground"]

EXPOSE 26379
