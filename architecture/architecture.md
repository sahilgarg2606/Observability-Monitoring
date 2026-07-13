                Users

                  │

          HTTPS (TLS)

                  │

              Nginx

                  │

          Grafana Dashboard

                  │

──────────────────────────────────────

        Prometheus

              │

      Alertmanager

              │

      Email Alerts

──────────────────────────────────────

OpenTelemetry Collector

        │         │

     Metrics    Traces

        │         │

 Prometheus     Tempo

──────────────────────────────────────

            Loki

             ▲

         Promtail

             ▲

Application Logs

──────────────────────────────────────

Blackbox Exporter

Node Exporter

cAdvisor

Redis Exporter

Postgres Exporter

API Health Checks

──────────────────────────────────────

Docker Compose