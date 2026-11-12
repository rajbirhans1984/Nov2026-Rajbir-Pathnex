# Day-10 - training

## Ansible Install Nginx on Pathnex Server

- name: Install Nginx on Pathnex server
  hosts: all
  become: yes
  tasks:
  - name: install Nginx
    yum:
    - name: Nginx
      state: present

docker --version
docker run ubuntu echo "Hello Pathnex"

FROM ubuntu:20.04
CMD ["echo", "Hello Pathnex"]
