# nginx-keepalived-ansible
You can deploy a high-available nginx setup using this playbook in just a minutue. make sure to change variables and inventory according to your environment.
example:
---
- hosts: all
  become: yes
  roles:
    - install
    - config
