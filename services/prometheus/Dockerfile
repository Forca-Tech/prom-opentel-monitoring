FROM prom/prometheus:latest

COPY prometheus.yaml /etc/prometheus/prometheus.yml
COPY alert_rules.yml /etc/prometheus/alert_rules.yml

EXPOSE 9090

VOLUME /data

CMD ["--config.file=/etc/prometheus/prometheus.yml"]
