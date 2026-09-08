# Kubernetes Basics Commands

This assignment covers the basic Kubernetes (`kubectl`) commands used to manage and interact with Kubernetes resources.

## Topics Covered

- Checking Kubernetes cluster information
- Creating and managing Pods
- Viewing Pods and other resources
- Describing Kubernetes resources
- Creating and managing Deployments
- Exposing applications using Services
- Checking resource status and logs
- Deleting Kubernetes resources

## Basic Commands

```bash
kubectl cluster-info
kubectl get pods
kubectl get deployments
kubectl get services
kubectl describe pod <pod-name>
kubectl logs <pod-name>
kubectl apply -f <file>.yaml
kubectl delete -f <file>.yaml
