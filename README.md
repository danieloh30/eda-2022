# Event-driven Architecture Day 2022

## Install KEDA v2

Deploying with Operator Hub - https://keda.sh/docs/2.6/deploy/#operatorhub

## knative-evnenting namespace

export KO_DOCKER_REPO=YOUR_CONTAINER_REGISTRY

For example, `export KO_DOCKER_REPO=quay.io/danieloh30`

ko apply -f quarkus-eda-knative-demo/kube/01-autoscaler-keda.yaml