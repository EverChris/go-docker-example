FROM index.tenxcloud.com/tenxcloud/golang

ADD . /go/src/go-docker-example/httpserver
RUN go install go-docker-example/httpserver
ENTRYPOINT /go/bin/httpserver

EXPOSE 8080