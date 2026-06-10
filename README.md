# ansible-monitoring-stack

Automated Linux infrastructure provisioning using Ansible with a full observability stack deployed via Docker Compose.

## What This Does

A single command provisions a Linux server, installs Docker, and deploys a complete monitoring stack:

## Stack

| Tool | Purpose |
|------|---------|
| Ansible | Infrastructure automation |
| Docker Compose | Container orchestration |
| Prometheus | Metrics collection |
| Grafana | Visualization & dashboards |
| Node Exporter | System metrics (CPU, RAM, Disk) |
| Alertmanager | Alerting & notifications |

## Structure

├── ansible/
│   ├── inventory/hosts.ini
│   └── playbooks/
│       ├── install-docker.yml
│       ├── deploy-monitoring.yml
│       └── full-setup.yml
└── monitoring/
├── docker-compose.yml
├── prometheus.yml
└── alertmanager.yml
