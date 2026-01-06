# Stack Tooling

Ce docker compose permet le lancement d'outils pour le monitoring et le stockage.

Les services présents dans ce docker-compose.yml :

- Grafana
- Prometheus
- Node Exporter (métriques du serveur)
- Smartctl Exporter (métriques SMART du stockage)
- Cadvisor (métriques conteneur)
- Filebrowser

Les dashboards Grafana utilisés :

- 22604 (smartctl exporter)
- 1860 (node exporter)
- 19908 (cadvisor)
