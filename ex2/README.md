# Create a Pod with a Liveness Probe


* See `liveness-probe-pod.yml` for an example description

* Start the pod

```bash
kubectl apply -f liveness-probe-pod.yml
```

* Check on the pod

Note: the name of the pod comes from the metadata in the yaml file
```bash
kubectl get pod whoami-liveness
kubectl describe pod whoami-liveness
kubectl logs whoami-liveness
```
