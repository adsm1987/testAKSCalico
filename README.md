# testAKSCalico

## Context

We need to ensure that the networking and network security solution (Calico) allows us to define the networking rules (policies) that we want to secure the cluster including ingress and egress.

## Setup

* Have a k8s cluster, for this case we will need an AKS cluster.
* Install [calicoctl](https://projectcalico.docs.tigera.io/maintenance/clis/calicoctl/install)
* When creating the AKS cluster make sure that you use calico as a network solution.
* Install an example application to make sure that the application is secure.

## Policies

