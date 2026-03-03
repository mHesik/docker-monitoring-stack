# My pet project: Server monitoring with Prometheus + Grafana + Node Exporter in Docker
A simple stack for monitoring server load (CPU, RAM, disk, network) using Docker Compose.

## What's inside
- Node Exporter — collects host metrics
- Prometheus — stores and scrapes metrics
- Grafana — beautiful dashboards

## How to run
1. `docker compose up -d`
2. Grafana: http://localhost:3000 (admin/admin)
3. Add Prometheus datasource: http://prometheus:9090
4. Import dashboard 1860 (Node Exporter Full)

## Structure
- `docker-compose.yml` — main compose
- `prometheus.yml` — Prometheus config