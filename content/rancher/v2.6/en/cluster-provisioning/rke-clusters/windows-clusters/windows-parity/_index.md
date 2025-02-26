---
title: Windows and Linux Cluster Feature Parity
weight: 3
---

Windows clusters do not share the same feature support as Linux clusters.

The following chart describes the feature parity between Windows and Linux on Rancher:

**Component** | **Linux** | **Windows**
--- | --- | ---
**Distributions** |  | 
RKE | Supported | Supported
RKE2 | Supported | In Preview in Rancher 2.6.0, General Availability Planned for Rancher 2.6.4
K3S | Supported | Not Supported
EKS | Supported | Not Supported
GKE | Supported | Not Supported
AKS | Supported | Not Supported
**Rancher Components** |  | 
Server | Supported | Not Supported
Agent | Supported | Supported
Fleet | Supported | Supported
EKS Operator | Supported | Not Supported
AKS Operator | Not Supported | Not Supported
GKE Operator | Not Supported | Not Supported
Alerting v1 | Supported | Supported
Monitoring v1 | Supported | Supported
Logging v1 | Supported | Supported
Monitoring/Alerting v2 | Supported | Supported
Logging v2 | Supported | Supported
Istio | Supported | Not Supported
Catalog v1 | Supported | Not Supported
Catalog v2 | Supported | Not Supported
OPA | Supported | Not Supported
Longhorn | Supported | Not Supported
CIS Scans | Supported | Not Supported
Backup/Restore Operator | Supported | Not Supported
**CNI / Add-ons** |  | 
Flannel | Supported | Supported
Canal | Supported | Not Supported
Calico | Supported | In Preview in Rancher 2.6.0, General Availability Planned for Rancher 2.6.4
Cilium | Supported | Not Supported
Multus | Supported | Not Supported
Traefik | Supported | Not Supported
NGINX Ingress | Supported | Not Supported

For updated information on feature support, you may visit [rancher/windows](https://github.com/rancher/windows) on GitHub.
