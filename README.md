# ansible-kubernetes

This a project for deploying kubernetes cluster (k8s).

## Getting Started

Fork/clone the repo to your local machine.

### Prerequisites

To use ansible playbook, you'll need to have ansible install on your master machine. No client is required on worker machines.

### Configuring

To configure the project to your specific needs modify hosts file, along with: ad_addr, user, group variables.
ad_addr sets the address of the kubernetes master
user and group are used to copy .kube directory to default user directory and to give default user access to kubernetes cluster.

## Deployment

To deploy kubernetes, use setup_master.yaml and setup_node.yaml playbooks.
