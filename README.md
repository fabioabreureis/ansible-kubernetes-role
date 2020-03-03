Ansible role for Kubernetes labs 
=========

This role will deploy a master and two workers for lab proposal. 

Requirements
------------

Ansible 2.4 or Higher


Playbook Example
--------------

```
- hosts: k8s
  become: true
  vars:
    - master_ip: 10.0.0.30
  roles:
    - ansible-kubernetes-role
```
