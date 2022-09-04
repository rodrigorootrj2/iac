iac-up:
	vagrant up
iac-down:
	vagrant destroy -f
iac-halt:
	vagrant halt -f	
web:
	vagrant up web	
db:
	vagrant up db
core:
	vagrant up core
httpd:	
	ansible-playbook  config/playbook-httpd.yaml -i config/hosts -u vagrant
mariadb:
	ansible-playbook  config/playbook-mariadb.yaml -i config/hosts -u vagrant
zabbix:
	ansible-playbook  config/playbook-zabbix.yaml -i config/hosts -u vagrant

