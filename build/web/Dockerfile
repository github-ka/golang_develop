FROM golang:latest

COPY go.mod go.sum /go/src/app/
WORKDIR /go/src/app
RUN go mod download

COPY . /go/src/app

CMD ["go", "run", "main.go"]
