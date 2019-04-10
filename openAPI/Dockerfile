FROM golang:1.8

RUN apt-get update

WORKDIR /go/src/app

COPY ./agave .

#RUN go-wrapper download   # "go get -d -v ./..."
#RUN go-wrapper install    # "go install -v ./..."

EXPOSE 8099

CMD ["go-wrapper", "run"] # ["app"]
ENTRYPOINT ["/bin/bash"]