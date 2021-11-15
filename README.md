# Network Container for AWX

Container for AWX containing functions necessary for network automation. Adds:

- pySNMP with the Ansible SNMP patch
- expect
- Ansible community.general
- Ansible netcommon
- Ansible cisco.ios
- PanOS support
- Postgresql client
- psycopg2/postgresql_query

May need set ansible_python_interpreter: /usr/bin/python3 for PanOS and postgresql_query to work properly
