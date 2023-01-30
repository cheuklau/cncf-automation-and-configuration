# cncf-automation-and-configuration

[Source](https://landscape.cncf.io/card-mode?category=automation-configuration)

## Introduction

- Speed up creation and configuration of compute resources e.g., VMs, networks, firewall rules, LBs, etc
- Infrastructure should be provisioned dynamically and without human intervention
- Reproduce environment setups with click of a button
- Manual setup is error prone
- Terraform reduce effort to scale servers and networks
- Puppet, Chef and Ansible provision servers and configure them and their applications programatically

## Tools Summary

| Tool | Status | Wiki | Summary | Hands-On |
|------|-------|------|---------|----------|
|Cloud Custodian|Incubating|[link](https://github.com/cheuklau/cncf-automation-and-configuration/wiki/Cloud-Custodian)|YAML-based rules for AWS resources| Yes |
|KubeEdge|Incubating|[link](https://github.com/kubeedge/kubeedge)|Edge nodes for k8s cluster| Yes |
|Ansible|Platinum|[link](https://github.com/cheuklau/cncf-automation-and-configuration/wiki/Ansible)|SSH for configuration management| Yes |

To-do:
- Cadence
- CDK for Kubernetes
- Chef
- devstream

Stopped looking at Kiosk. Ignore not open-source or tools with enterprise version.
