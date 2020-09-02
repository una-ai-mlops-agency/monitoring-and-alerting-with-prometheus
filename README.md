# Monitoring-and-Alerting-with-Prometheus

## Usage
Clone this repository

Cd to the cloned repository and run:

```bash
docker-compose up
```

That's it, it deploys the entire Grafana and Prometheus stack. By default you have cAdvisor and node-exporter.

Prometheus is now accessible via http://0.0.0.0:9090

The Grafana Dashboard is now accessible via http://0.0.0.0:3000
```
username - admin
password - foobar
```