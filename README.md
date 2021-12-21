# Zabbyz
documentação zabbyz

comandos usados.
1521  sudo apt install -y zabbix-agent<br/>
 1522  dpkg -L zabbix-agent<br/>
 1523  dpkg -L zabbix-agent | less<br/>
 1524  cd /etc/zabbix<br/>
 1525  ls<br/>
 1526  sudo vim zabbix_agentd.conf<br/>
 1527  ss -tnl<br/>
 1528  sudo ss -tnlp<br/>
 1529  sudo vim /etc/zabbix/zabbix_agentd.conf<br/>
 1530  ss -tnl | grep 10050<br/>
 1531  systemctl list-units zabbix*<br/>
 1532  systemctl list-units 'zabbix*'<br/>
 1533  sudo systemctl reload zabbix-agent.service<br/>
 1534  sudo systemctl restart zabbix-agent.service<br/>
 1535  sudo systemctl status zabbix-agent.se<br/>
