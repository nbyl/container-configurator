# container-configurator

Deploy config files into kubernetes/OpenShift secrets.

## Prequisites

- a working OpenShift Cluster
- OpenShift Client Tools installed
- [Helm CLI](https://helm.sh)
- [Tiller](https://blog.openshift.com/getting-started-helm-openshift/)

## Installation

    helm upgrade --install myconfig .

This will install the files from `configuration` into a secret and output it's name.