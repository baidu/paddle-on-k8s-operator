# paddle-on-k8s-operator

## Get Started

We use `dep` for dependency management, to compile the project:

```
dep ensure -v

cd ./cmd/operator

CGO_ENABLED=0 GOOS=linux GOARCH=amd64 go build

./operator -kubeconfig ~/.kube/config -autoclean

```

## Overview



## Contributing

