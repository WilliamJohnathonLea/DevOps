# Local DevOps

## Metrics and Tracing
Metrics and Tracing are provided by Prometheus and Tempo.

To view your metrics and traces you can go to [the local Grafana server](http://localhost:3000) which has Prometheus and Tempo configured as data sources.

### Configuring Prometheus
You can configure Prometheus by editting the [prometheus.yaml](prometheus/prometheus.yaml) file.

### Configuring Tempo
You can configure Tempo by editting the [tempo.yaml](tempo/tempo.yaml) file.

## Logs
Logs are provided by Loki amd Promtail.

To view your logs you can go to [the local Grafana server](http://localhost:3000) which has Loki configured as a data source.

### Configuring Loki
You can configure Loki by editting the [loki.yaml](loki/loki.yaml) file.

### Configuring Promtail
You can configure Promtail by editting the [promtail.yaml](promtail/promtail.yaml) file.

## Running the stack
Use `docker-compose up -d` to start the stack and use `docker-compose down -v` to destroy it.
