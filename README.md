# prom-monitoring-stack

Stack monitoring Prometheus AlertManager

## Notice

- Replace "localhost" from  prometheus.yml if you want to use docker-compose
- Download node_exporter <https://github.com/prometheus/node_exporter/releases>

## Command

### running

> docker-compose up

## Access

- Prometheus: < IP >:9090
- AlertManager: < IP >:9093
- cAdvisor: < IP >:8590
- node_Exporter: < IP >:9100

## TODO

    [ ] Express prometheus.yml targets as external files
