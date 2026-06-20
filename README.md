# Cloud Infrastructure Monitoring & Alerting Platform

## Overview

Built a cloud-based monitoring solution on AWS EC2 using Prometheus, Grafana, and Node Exporter. The platform provides real-time infrastructure monitoring, dashboard visualization, and automated alerting for system health metrics.

## Technologies Used

* AWS EC2
* Linux
* Docker
* Docker Compose
* Prometheus
* Grafana
* Node Exporter

## Features

* Real-time CPU, Memory, Disk, and Network Monitoring
* Grafana Dashboards for Infrastructure Visualization
* Prometheus Metrics Collection
* Automated Alert Rules
* Dockerized Deployment
* Persistent Grafana Storage using Docker Volumes

## Alert Rules

* High CPU Usage (>80%)
* High Memory Usage (>80%)
* Node Exporter Down

## Architecture

Node Exporter → Prometheus → Grafana → Alerting

## Run the Project

```bash
docker-compose up -d
```

## Learning Outcomes

* Infrastructure Monitoring
* Prometheus & Grafana
* Docker & Docker Compose
* AWS EC2 Administration
* Observability & Alerting
