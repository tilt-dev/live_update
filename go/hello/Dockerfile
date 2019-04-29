FROM golang:1.12

ADD . /app/src

WORKDIR /app/src

RUN go version

RUN cd /app/src && go install .

ENTRYPOINT /go/bin/hello

EXPOSE 5000