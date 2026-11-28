# Day-27-training

## Ansible Install Nginx on codefly server

- name: Install Nginx on codefly Server
  hosts: all
  become: yes
  tasks:
- name: Install Nginx
  yum:
  name: Nginx
  state: present

## Docker --version

docker run ubuntu echo "Hello Codefly"

FROM ubuntu:20.04
CMD ["echo", "Hello Codefly"]
