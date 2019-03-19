  <h1>ZABBIX-VARNISH-PLUS</h1>

Based on https://github.com/EXPIM/zabbix-varnish

Basic varnish monitoring template and config file for zabbix

Usage instructions are as simple as:

allow zabbix to run scripts with varnish permissions by adding to group: #usermod -a --groups varnish zabbix
upload userparameters to /etc/zabbix/zabbix-agent.d/
import template into zabbix and attach to vm which has varnish installed and running

<h2>plus features:</h2>

  <h4>graphics:</h4>
  - Varnish Fetch Fails
  - Varnish HIT/MISS

  <h4>itens:</h4>
  - Varnish Fetch Fails (NEW)
  - Varnish Fetch Fails (TOTAL)
  - Varnish Cache Hits (%)
  - Varnish Cache Miss (%)

  <h4>triggers:</h4>
  - Varnish Fetch Fails
