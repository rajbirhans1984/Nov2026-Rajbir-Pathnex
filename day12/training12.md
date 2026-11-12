# Day12 - training

## Ansible Install Nginx on codefly server

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

## docker --version

- docker run ubuntu echo "echo codefly consultancy"

FROM ubuntu:20.04
CMD ["echo", "hello codefly"]
