FROM debian:stable-slim

COPY bin/event_exporter /

USER nobody

ENTRYPOINT ["/event_exporter"]

EXPOSE 9102
