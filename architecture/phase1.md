                         USER

                           │

                     Grafana :3000

                           │

                     Prometheus :9090

        ┌────────────┬──────────────┬───────────────┐
        │            │              │
        ▼            ▼              ▼

 Node Exporter   cAdvisor   Blackbox Exporter

        │            │              │
        │            │              │

 Linux Host    Docker Metrics    Health APIs

                                    │
                 ┌──────────────────┴──────────────────┐
                 │                                     │

 invoice.nyife.chat/api/v1/health

 backend.nyife.chat/health