iac-up:
	vagrant up
iac-down:
	vagrant destroy -f
iac-halt:
	vagrant halt -f	
core:
	vagrant up core
zabbix:
	ansible-playbook  config/playbook-zabbix.yaml -i config/hosts -u vagrant

