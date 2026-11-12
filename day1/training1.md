# Day-1 - training

## Ansible Task - Install Nginx on Pathnex Server

- name: Install Nginx on Pathnex Server
  hosts: all
  become: yes
  task:
  - name: Install Nginx
    yum:
    name: Nginx
    state: present

# how to check docker version and installation

docker --version
docker run ubuntu echo "hello india"

From ubuntu:20.04
CMD["echo", "Hello pathnex"]
