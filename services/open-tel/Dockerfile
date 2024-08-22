FROM otel/opentelemetry-collector:latest

COPY otel-collector-config.yaml /etc/otel-collector-config.yaml

EXPOSE 8888 8889 8080

ENTRYPOINT ["/otelcol"]
CMD ["--config=/etc/otel-collector-config.yaml"]