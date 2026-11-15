# Day-15 - training

## Ansible Install Nginx on pathnex server

- name: Install Nginx on pathnex server
  hosts: all
  become: yes
  - name: Install Nginx
    yum:
    name: nginx
    state: present

Docker --version
docker run ubuntu echo "Hello pathnex"

FROM ubuntu:20.04
CMD ["echo", "Hello Pathnex"]
