# NetMon - Network Monitoring System


This is a simple bash script for quickly setting up a server monitoring system using Prometheus, Node Exporter, and Grafana. By running this script, you can set up your monitoring system in a short amount of time and configure pre-built dashboards for viewing system metrics in Grafana.


# Features:

- Installs and configures the latest versions of:
   - Prometheus for monitoring and alerting.
   - Node Exporter for collecting system metrics.
   - Grafana for data visualization and analysis.



# Installation :

```
curl -sSL https://github.com/Niihil/NetMon/raw/main/run | bash

```


# Access the Monitoring Tools:

- Grafana:
    - URL: http://<your-server-ip>:3000
    - Default username: admin
    - Default password: admin

- Prometheus:
    - URL: http://<your-server-ip>:9090

- Node Exporter Metrics:
    - URL: http://<your-server-ip>:9100/metrics
