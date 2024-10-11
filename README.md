# Odyssey metrics issue

To reproduce:
- `docker build -t odyssey .`
- `docker compose up -d`
- `curl localhost:3422/metrics`
- See the metrics is empty
