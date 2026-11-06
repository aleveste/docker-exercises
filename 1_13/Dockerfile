FROM golang:1.20-alpine
WORKDIR /usr/src/app
COPY . .
RUN go build -o server .
EXPOSE 8080
CMD ["./server"]