# kubernetes-playground

Collection of experiments, tests and other "things" with kubernetes

## Setup
Will use [minikube](https://minikube.sigs.k8s.io/) since it's cross platorm

After installation and running `minikube start` it'll automatically add `.kube/config` configuration in order to use the cluster.

At this point, running `kubectl get nodes` should output something like:
```shell
kubectl get nodes
NAME       STATUS   ROLES                  AGE    VERSION
minikube   Ready    control-plane,master   6m8s   v1.23.3
```
