# Grafana OpenTelemetry Stack

Docker Compose configuration to run a Grafana cluster that will accept logs, metrics and traces from an OpenTelemetry collector.

Runs the following services:
  - Loki (accepts logs)
  - Prometheus (accepts metrics)
  - Tempo (accepts Traces)

See [otel-local-config.yaml](./examples/otel-local-config.yaml) for an example config indicating how to export data to this cluster.
