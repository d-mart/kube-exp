# Getting Started

### Get docker

Install [docker for mac](https://docs.docker.com/docker-for-mac/)

### Enable kubernetes

Enable kubernetes in [docker config](https://www.techrepublic.com/article/how-to-add-kubernetes-support-to-docker-desktop/)

Here is a [another walkthru](https://medium.com/backbase/kubernetes-in-local-the-easy-way-f8ef2b98be68) but I think you can skip the "make an account and sign in parts"

### Check / Set current context

```bash
$ kubectl config current-context
error: current-context is not set

$ kubectl config use-context docker-for-desktop
Switched to context "docker-desktop".
```

### Setup kubernetes dashboard

Here is [a walkthru](https://kubernetes.io/docs/tasks/access-application-cluster/web-ui-dashboard/)

```bash
kubectl apply -f https://raw.githubusercontent.com/kubernetes/dashboard/v2.0.0/aio/deploy/recommended.yaml

```
