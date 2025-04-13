# Monitoring-and-Alerting-with-Prometheus

## Setup
Clone this repository

Cd to the cloned repository and run:

```bash
HOSTNAME=$(hostname) docker-compose up
```

It deploys the entire Grafana and Prometheus stack. By default you have cAdvisor and node-exporter.

Prometheus is now accessible via http://0.0.0.0:9090

The Grafana Dashboard is now accessible via http://0.0.0.0:3000
```
username - admin
password - foobar
```
Webapp is now accessible via http://0.0.0.0:5000

## Usage 
Follow the workshop [here](https://github.com/una-ai-mlops-agency/monitoring-and-alerting-with-prometheus/tree/main/steps)
