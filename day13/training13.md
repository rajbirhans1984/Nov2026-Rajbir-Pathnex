# Day-13 - Training

## Ansible Install Nginx on codefly server

- name: Install Nginx on Codefly Server
  hosts: all
  become: yes
  tasks:
- name: Install Nginx
  yum:
  name: Nginx
  state: present

## docker --version

- docker run ubuntu echo "Hello Codefly"

FROM ubuntu:20.04
CMD ["echo", "Hello codefly"]
