FROM golang:latest

WORKDIR /app
COPY . .

RUN go build -o main .

EXPOSE 9080

ENV MONGO_DB_HOST mongodb

CMD ["./main"]
