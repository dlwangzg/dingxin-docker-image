FROM leading/alpine:3.7
MAINTAINER Daliu <liuyg@leadingsoft.com>

WORKDIR /app/codis-dashboard

#RUN apk add --no-cache bash

COPY target ./

CMD ["./admin/codis-dashboard-admin.sh", "start-foreground"]

EXPOSE 18080
