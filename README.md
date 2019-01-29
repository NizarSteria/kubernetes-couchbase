# kubernetes-couchbase
= Pre-configured Couchbase Docker Container

These are the artifacts to create a pre-configured Couchbase Docker image.

== Build the image

```console
docker build -t harounaouissaoui/kubernetes-couchbase:k8s .
```

== Start the pod

Start the pod as:

```console
kubectl create -f couchbase-pod.yml
```