FROM golang:1.8

WORKDIR /go/src/siagw
COPY . .

RUN go get -v ./...
RUN go build

CMD ["siagw"]