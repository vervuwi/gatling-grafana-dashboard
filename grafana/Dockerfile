FROM grafana/grafana:7.3.7

COPY --chown=472:472 grafana.ini /etc/grafana/grafana.ini
COPY --chown=472:472 plugins /var/lib/grafana/plugins
COPY --chown=472:472 provisioning /etc/grafana/provisioning