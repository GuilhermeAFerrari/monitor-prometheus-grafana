FROM prom/prometheus:v2.17.1 as image-prometheus-base
COPY ./prometheus.yml /etc/prometheus
COPY ./alert.rules.yml /etc/prometheus

VOLUME ./data
EXPOSE 9090