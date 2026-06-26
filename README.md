# Promithious_And_Grafana

Monitoring tool


Prometheus  ← scrapes ← Node Exporter, cAdvisor, OTEL Collector

Loki        ← pushes  ← Promtail (container logs)

OTEL        ← OTLP    → exports metrics to Prometheus

Grafana     → queries  → Prometheus + Loki (auto-provisioned)

Notes App   → demo workload

