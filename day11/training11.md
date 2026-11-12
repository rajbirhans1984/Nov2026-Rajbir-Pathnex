# Day-11 - training

## Ansible Install Nginx on pathnex server

- name: install Nginx on pathnex server
  hosts: all
  become: yes
  tasks:
- name: Install Nginx
  yum:
- name: Nginx
  state: present

  docker --version
  docker run ubuntu echo "Hello pathnex"

  FROM ubuntu:20.04
  CMD ["echo", "Hello Pathnex"]
