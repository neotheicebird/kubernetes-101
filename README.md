# kubernetes-101
Learnings on kubernetes


## What is a cluster?

A cluster is a collection of nodes that work as a single unit. Each node in a cluster could be physically separated computers or software isolated compute units. The abstractions in Kubernetes allow you to deploy containerized applications to a cluster without tying them specifically to individual machines

## What is kubernetes?

Kubernetes is a tool that coordinates the nodes in a cluster. It makes sure the cluster is in or is actively transforming towards a desired state. A Kubernetes cluster consists of two types of resources:

The Master coordinates the cluster
Nodes are the workers that run applications

## Minikube?

Minikube is a lightweight Kubernetes implementation that creates a VM on your local machine and deploys a simple cluster containing only one node.


