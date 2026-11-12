# Day12 - training

## Ansible Install Nginx on pathnex server

- name: Install Nginx on AWS server
  hosts: all
  become: yes
  tasks:
  - name: Install Nginx
    yum:
    - name: Ngnix
      state: present
- name: start Nginx Service
  service:
  name: Nginx
  state: started
  enabled: yes
