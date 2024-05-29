# Running a playbook

```
ansible-playbook h002.yml -i 10.10.20.48, -c ansible.netcommon.network_cli -u developer -k -e ansible_network_os=cisco.ios.ios
````

# Inventory and Gathering facts

```
ansible-playbook h002-2.yml -i inventory.yml -k
```