FROM index.tenxcloud.com/tenxcloud/golang

ADD . /go/src/go-docker-example/chatroom
RUN go install go-docker-example/chatroom/server.go
ENTRYPOINT /go/bin/server

EXPOSE 4040