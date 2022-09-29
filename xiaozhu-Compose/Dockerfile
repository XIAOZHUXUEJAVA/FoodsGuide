FROM golang:latest

RUN mkdir /app

WORKDIR /app

ADD . /app

RUN go build -o main ./server.go

EXPOSE 9090

CMD /app/main