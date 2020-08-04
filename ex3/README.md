# Creating a Service

* See `whoami-svc.yml`
* I named the metadata and app selector with hints (differently than the book) to make it more clear where they're used later.

## Create the service

```bash
kubectl create -f whoami-svc.yml
```

## Inspect the service

```bash
kubectl get service
# or, via shorthand and aliases:
k get svc
```
