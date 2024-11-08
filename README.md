# Grafana OpenTelemetry Stack

Docker Compose configuration to run a Grafana cluster that will accept logs, metrics and traces from an OpenTelemetry collector.

Runs the following services:
  - Grafana (app to query data from the other services)
  - OpenTelemetry Collector (accepts and processes OpenTelemetry data, and exports it to Loki, Prometheus and Tempo)
  - Loki (accepts logs)
  - Prometheus (accepts metrics)
  - Tempo (accepts Traces)
