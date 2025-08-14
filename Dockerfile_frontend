FROM golang:latest

WORKDIR /usr/src/app

COPY frontend/ .

#ENV BACKEND_DNS="backend_container"

RUN go build frontend

EXPOSE 8080

CMD ["go", "run", "frontend"]