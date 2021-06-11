FROM golang:latest
ADD ./app /go/src/app
RUN mkdir /app
WORKDIR /app
RUN go build -o main app/app-name
CMD ["/app/main"]
EXPOSE 8080