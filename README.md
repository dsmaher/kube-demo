This will set up a simple example of a microservice architecture on Kubernetes.

# Kubernetes sample microservice deployment

Install [Minikube](https://github.com/kubernetes/minikube) and create your cluster.
You will need at least *8 GB RAM* allocated to your cluster.

Run the follwing to spin up everything in your cluster:

```bash
kubectl apply -f .
```

To bring it all down again:
```bash
kubectl delete -f .
```

## Exposed Ports

| Service            | Port                 |
|--------------------|----------------------|
| kafka-manager      | 31000                |
