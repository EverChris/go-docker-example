FROM index.tenxcloud.com/docker_library/golang

ADD . /go/src/go-docker-example/chatroom
RUN go install go-docker-example/chatroom
ENTRYPOINT /go/bin/chatroom

EXPOSE 4040