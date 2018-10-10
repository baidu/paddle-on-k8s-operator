# paddle-on-k8s-operator

## Get Started

We use `dep` for dependency management, to compile the project:

```
dep ensure -v

cd ./cmd/operator

CGO_ENABLED=0 GOOS=linux GOARCH=amd64 go build

./operator -kubeconfig ~/.kube/config -autoclean

```

You can have a quick start by using `example/examplejob.yaml`.

You can also try to use new gang-scheduling mode to schedule your trainingjob, first you can follow [this link](https://github.com/kubernetes-sigs/kube-batch/blob/master/doc/usage/tutorial.md) to start up the kube-batch in helm, and then try `example/examplejob_with_kube_batch.yaml`.


## License

paddle-on-k8s-operator is under the [Apache-2.0 license](LICENSE).

