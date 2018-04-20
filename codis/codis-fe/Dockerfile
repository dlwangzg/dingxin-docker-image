FROM leading/alpine:3.7
MAINTAINER Daliu <liuyg@leadingsoft.com>

WORKDIR /app/codis-fe

#RUN apk add --no-cache bash

COPY target ./

CMD ["./admin/codis-fe-admin.sh", "start-foreground"]

EXPOSE 8080
