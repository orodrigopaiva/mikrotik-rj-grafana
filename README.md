# MikroTik RJ - Grafana Dashboard

Projeto do dashboard operacional do MikroTik RJ usando Grafana + Zabbix.

## Objetivo

Centralizar e versionar os arquivos do dashboard do MikroTik RJ.

## Componentes monitorados

- RouterBOARD hEX / portas físicas
- Links VIVO e WEBCENTRO
- Status PPPoE Webcentro
- VPN IPsec RJ-SP
- DDNS RJ
- NAT DVR / Control iD
- Mangle de rotas
- DHCP leases
- ARP
- Bridge hosts
- Top destinos ativos
- Eventos recentes
- AdBlock RJ

## Estrutura prevista

```text
dashboards/
panels/
zabbix-items/
mikrotik-scripts/
docs/
