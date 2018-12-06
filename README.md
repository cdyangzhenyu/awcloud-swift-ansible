# awcloud-swift-ansible

ansible-playbook -i inventory/hosts.ini cluster.yml
ansible-playbook -i inventory/hosts.ini swift_proxy_update_config.yml
ansible-playbook -i inventory/hosts.ini swift_storage_update_config.yml

### add new storage node, edit host.ini

ansible-playbook -i inventory/hosts.ini swift_proxy_update_config.yml
ansible-playbook -i inventory/hosts.ini swift_storage_update_config.yml