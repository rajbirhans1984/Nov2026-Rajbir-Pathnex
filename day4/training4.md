# Day-4 - training

## Ansible Task - Install Nginx on Pathnex server

- name: Install Nginx on Pathnex Server
  hosts: all
  become: yes
  tasks:
  - name: Install Nginx
    yum:
    name: Nginx
    state: present

docker --version
docker run ubuntu echo "Hello Pathnex"

FROM ubuntu:20.04
CMD ["echo", "Hello Pathnex"]
