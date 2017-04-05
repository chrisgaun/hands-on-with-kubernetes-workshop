# Hands on with Kubernetes Workshops

The following repository will create you a Kubernetes cluster using the following:

1. Digital Ocean for the underlying infrastructure
2. Terraform to create the infrastructure
3. [Kismatic Enterprise Toolkit](https://github.com/apprenda/kismatic) for provisioning our Kubernetes cluster

## Prerequisities

A list of prerequisities for Mac can be found [here](docs/1-mac-prerequisities.md)

A list of prerequisities for Windows can be found [here](docs/2-windows-prerequisities.md)

## Create Infrastructure & Provision Cluster

A list of steps to build and provision the Kubernetes cluster can be found [here](docs/3-build-cluster.md)

## Using Kubernetes

The presenter will go through a list of demos during the workshop.

## Destroying everything once finished

To remove the droplets from Digital Ocean execute the following from your local machine.

```
$ cd terraform
$ terraform destroy --force
```
## Reference

Kubernetes vs. Mesos Marathon vs. Docker Swarm vs. Cloud Foundry SWOT analysis found [here](https://apprenda.com/white-papers/container-orchestration-comparison-guide/)

Learn Why CTO's and Developers are Choosing Kubernetes [here](https://apprenda.com/why-kubernetes/)

Join the Kubernetes community [here](https://github.com/chrisgaun/GKE-hands-on-training/blob/master/community.md)
