# day21 - training

## Ansible Install Nginx on codefly server

- name: Install Nginx on codefly server
  hosts: all
  become: yes
  tasks:
- name: install Nginx
  yum:
  name: Nginx
  become: present

## docker --version

docker run ubuntu echo "Hello codefly"

FROM ubuntu:20.04
CMD["echo", "Hello Codefly"]
