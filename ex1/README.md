# Simple ReplicaSet



## image

This example uses a simple pre-made container image that just echoes information about the request and the container

https://hub.docker.com/r/containous/whoami



## create a replica set

```bash
kubectl apply -f replica-set.yml
```



## get info about the running containers

```bash
❯ kubectl get pods --all-namespaces -o jsonpath="{..image}" | tr ' ' '\n'
```




