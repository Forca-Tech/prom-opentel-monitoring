FROM otel/opentelemetry-collector:latest

COPY otel-collector-config.yaml /etc/otel-collector-config.yaml

EXPOSE 1888 8888 8889 13133 4317 4318 55679

ENTRYPOINT ["/otelcol"]
CMD ["--config=/etc/otel-collector-config.yaml"]