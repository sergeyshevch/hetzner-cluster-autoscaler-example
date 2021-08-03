# Hetzner cluster autoscaler example

This repo contains HELM chart for bootstraping cluster autoscaler with HCLOUD provider.

Chart includes:
* Cluster autoscaler
* Overprovisioning
* Grafana dashboard
* RBAC roles for CSI driver
* Init script for following cluster setup:
  
* Dockerless (containerd only)
* HA master nodes with nginx proxy on every worker
* K8S_VERSION="1.20.5-00"
* CONTAINERD_VERSION="1.4.4-1"
* Kubelet settings