# Metrics from Spark

## Setup

- drivers and executors emit metrics into sinks (JMX)
- JMX exposes metrics to Prometheus
- Grafana visualizes metrics from Prometheus

# How

- [link](https://dzlab.github.io/bigdata/2020/07/03/spark3-monitoring-2/)
- Spark needs to be updated to version 3 or higher
- Extra plugins should be installed

# Plugins

- Extends Spark metrics with custom code
- CERN has already implemented cloud storage (S3) metrics [link](https://github.com/cerndb/SparkPlugins)
