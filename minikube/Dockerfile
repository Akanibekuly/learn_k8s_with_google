FROM golang:alpine

WORKDIR $GOPATH/src/github.com/medyagh/local-dev-example-with-minikube/

COPY . . 

RUN  go install -v ./...

EXPOSE 8080

CMD ["local-dev-example-with-minikube"]