# Ansible Monitoring Stack

An automated Linux monitoring platform built with Ansible, Docker, Prometheus, Grafana, Node Exporter, and Alertmanager.

## Features

* Infrastructure automation using Ansible
* Docker-based deployment
* Prometheus metrics collection
* Grafana dashboards and visualization
* Node Exporter system monitoring
* Alertmanager integration for alerting
* One-command deployment using Ansible playbooks

## Architecture

Ansible → Docker → Prometheus → Grafana
-> Node Exporter
-> Alertmanager

## Project Structure

```text
ansible-monitoring-stack/
├── ansible/
│   ├── inventory/
│   └── playbooks/
│       ├── install-docker.yml
│       ├── deploy-monitoring.yml
│       └── full-setup.yml
├── monitoring/
│   ├── docker-compose.yml
│   ├── prometheus.yml
│   └── alertmanager.yml
└── README.md
```

## Tech Stack

Ansible • Docker • Prometheus • Grafana • Node Exporter • Alertmanager • Linux
