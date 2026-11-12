# Day-2 - training

## Ansible Task: Install Nginx on Pathnex Server

- name: install Nginx Pathnex Server
  hosts: all
  become: yes
  task:
  - name: Install Nginx
    yum:
    - name: Nginx
      state: present

# how to check docker version and installation

docker --version
docker run ubuntu echo "Hello Pathnex"

FROM ubuntu:20.04
CMD ["echo","hello India"]
