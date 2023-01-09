# starlink_metrics
Starlink dishy metrics in Grafana.

Used with [Starlink exporter](https://github.com/ewilken/starlink-exporter) so thanks to ewilken for the exporter itself ad the dashboard.

Usage:

1. Make sure you have docker-compose or version of docker with `docker compose`
2. Run it `docker-compose up` or `docker compose`. Do not forget to add `-d` if you want to run it in background. For the first run runnin in foreground might be a good idea, just to be sure there is no errors.
3. Visit [local grafana](http://localhost:3000)


Default settings:
1. Starlink URL `http:dishy.starlink.com:9200`
2. Retention for prometheus: 1 week
3. Scrape interval: 15 seconds
4. Prometheus persistent directory: ./prom_data
4. Grafana's creds admin/12345
