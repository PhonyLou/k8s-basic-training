# k8s-basic-training

Target: Build basic k8s service knowledge & concept.

We will discuss about: 
- pod
- namespace
- kubectl
- ingress / service / deployment / cronjob[Optional]
- dashboard[Optional]

## Workshop

### Prerequisites

- Docker
- Kubectl => `brew install kubectl`
- MiniKube => `brew install minikube`

### Get start

To start your cluster, you can use `minikube start`. Once it done, you will get the "minikube" cluster and the "default" namespace.

Before we jump into further details, let's go to the dashboard to get a general overview.

```
$ minikube dashboard
```
