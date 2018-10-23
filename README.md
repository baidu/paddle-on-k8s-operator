# paddle-on-k8s-operator

## Prerequisites

* Kubernetes Version 1.8+.

Paddle on Kubernetes Operator relies on CRD and garbage collection which are supported in Kubernetes 1.8+.

## Get Started

For operator installation and usage, please checkout [Quick Start Guide](docs/quick-start-guide.md).

For detailed information of how to use operator, please check out [User Guide](docs/user-guide.md).

For detailed design documentation, please check out [Design](docs/design.md).

For detailed api specifications, please check out [Api](docs/api.md).

## Overview

The Paddle Operator tries to run PaddlePaddle training job as native as other workloads on Kubernetes. It relies on CRD for specifying the PaddlePaddle training job.

Features including:

* Paddle training job instance auto scaling according to resource utilization
* Paddle training job instance fault tolerant

## Contributing

For contributing to this project, please check out [CONTRIBUTING](CONTRIBUTING.md) first, then check out [Developer Guide](docs/developer-guide.md).

## License

paddle-on-k8s-operator is under the [Apache-2.0 license](LICENSE).

