# home-network-architechture

Architecture of Home Network

:warning: **Under Constructing**

## Overview

All we need a daily-use infrastructure as below:

- Elastic
    - Provision disposable Linux containers instantly in home
    - Host servers instantly in home
- Reliable
    - High Availability
- Operable
    - Logging
    - Monitoring
    - Alerting
- Secure
- IaC

This repository aims to describe architectures / documents / codes
how to build the infrastructure in my home.

### Components

TBU

- Physical Networking
    - Link Aggregation
    - VLAN
- Container Hosting
    - LXC on Proxmox VE
    - or Docker
- Container Orchestration
    - Kubernetes
- Monitoring
    - Prometheus
- Object Storage
    - Ceph
    - or MinIO
- Handling Outbound Traffic
    - Cloudflare Tunnel
    - WireGuard

## Index

- Architecture Overview
    1. [Physical Network](./docs/01_physical_network/)

## Reference

TBU

## LICENSE

MIT
