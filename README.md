# Beszel Helm Chart

This Helm chart installs [Beszel](https://github.com/henrygd/beszel) — a lightweight, self-hosted server and container monitoring hub — into a Kubernetes cluster. It provides a real-time dashboard, historical stats, and optional agent support for node-level metrics.

## Features

- Web-based monitoring dashboard
- System and container metrics (CPU, memory, disk, network, GPU)
- Lightweight, single-binary hub
- Optional `DaemonSet` agent for enhanced node monitoring
- Supports Docker and Podman
- Optional Ingress and PVC support