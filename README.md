# Reproduction of lossy log ingestion to Loki (Grafana Cloud)

Run this using

```bash
CLUSTER_ENVIRONMENT=localhost \
password= \
user= \
uri \
vector -c vector.yaml
```

You will see that only the first message gets ingested if you remove the `protocol.batch.max_events` line
