zabbix-varnish

Based on https://github.com/EXPIM/zabbix-varnish

Basic varnish monitoring template and config file for zabbix

Usage instructions are as simple as:

allow zabbix to run scripts with varnish permissions by adding to group: #usermod -a --groups varnish zabbix
upload userparameters to /etc/zabbix/zabbix-agent.d/
import template into zabbix and attach to vm which has varnish installed and running

plus features:

  graphics:
  - Varnish Fetch Fails
  - Varnish HIT/MISS

  itens:
  - Varnish Fetch Fails (NEW)
  - Varnish Fetch Fails (TOTAL)
  - Varnish Cache Hits (%)
  - Varnish Cache Miss (%)

  triggers:
  - Varnish Fetch Fails
