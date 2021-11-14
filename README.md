# ansible-recent2
install and setup https://pypi.org/project/recent2/

to use the playbook simply issue:
```
ansible-playbook -i inventory.ini recent2-install.yml
ansible-playbook -i inventory.ini recent2-configure-bashrc.yml
```

which will install and configure recent2 globally on hosts provided in inventory.ini file.
