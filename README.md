# Ansible for Metricbeats

* Start metricbeats on the nodes indicated in hosts2: ansible-playbook playbook.yml -i hosts2 --tags "start"
* Stop metricbeats on the nodes indicated in hosts2: ansible-playbook playbook.yml -i hosts2 --tags "stop"
* Re-Start metricbeats on the nodes indicated in hosts2: ansible-playbook playbook.yml -i hosts2 --tags "restart"