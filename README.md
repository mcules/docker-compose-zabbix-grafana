# docker-compose-zabbix-grafana

Dieses compose-file setzt voraus das ihr einen funktionierenden Traefik service mit dem Netznamen "proxy" laufen habt.
Falls ihr andere Einstellungen habt oder keinen Traefik nutzt, müsst ihr den Stack entsprechend anpassen.

In der .env müsst ihr noch eure URL's anpassen.
Die Passwörter solltet ihr bei der Gelegenheit ebenfalls gleich mit ändern ;)

Falls ihr noch kein Docker installiert habt, gibt es [hier](https://blog.denniseisold.de/blog/2023/03/15/docker-snippets/) noch ein paar Snippets dazu.

## Zugangsdaten

### Grafana
`admin:admin`

### Zabbix
`Admin:zabbix`