# Jelastic-Zabbix-server
Installs and configures Zabbix 5 on a new Environment.

The Software Stack is LLSMP so Litespeed and MariaDB (see https://docs.jelastic.com/lemp-llsmp)

The installation is based on centos 7 and due to poor packages of zabbix alot is done manually unfortunately.
For example the frontend is directly stripped from their gitlab and downloaded using a zip archive in this github.

# Installation
Simply import this link using the Jelastic JPS Import function:
```
https://raw.githubusercontent.com/panslothda/Jelastic-Zabbix-server/master/main.jps
```

Or copy the content of it into the import window.

