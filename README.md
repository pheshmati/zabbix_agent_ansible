Zabbix-agent-installation
------

Example Inventory ==> /etc/ansible/hosts
------
[zabbix_nodes]
your_server_hostname ansible_host=192.168.231.91 (ip_server)

Example Playbook
```
- hosts:
   - zabbix_nodes
 ```
```
roles:
- zabbix-agent-installation
```
