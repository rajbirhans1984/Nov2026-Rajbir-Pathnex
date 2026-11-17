# Day-17-Training

## Ansible Install Nginx on codefly Server

- name: Install Nginx on codefly server
  hosts: all
  become: yes
  tasks:
- name: install Nginx
  yum:
  name: Nginx
  state: present

## docker --version

docker run ubuntu echo "Hello Codefly"

FROM ubuntu: 20.04

CMD ["echo", "Hello Codefly"]
