# helm-kubernetes-registry

## Description

This helm create registry secret for pulling Docker images from external registry.

## Installation

Install example-registry-secret chart in your namespace.

```
$ helm upgrade example-registry-secret --install ./helm/example-registry-secret --namespace your-namespace
```

## Upgrade

Upgrade example-registry-secret in **openfaas-fn** namespace.

```
$ helm upgrade example-registry-secret --install ./helm/example-registry-secret --namespace your-namespace
```

## Delete

Soft:

```
$ helm delete example-registry-secret
```

Hard:

```
$ helm delete --purge example-registry-secret
```
