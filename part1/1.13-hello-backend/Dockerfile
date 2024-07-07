FROM golang:latest

WORKDIR /usr/src/app

COPY . .

RUN go build

ENV REQUEST_ORIGIN="*"

EXPOSE 8080

CMD [ "./server" ]

