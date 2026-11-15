# Day 14 - training

## Ansible Install Nginx on pathnex server

- name: Install Nginx on pathnex server
  hosts: all
  become: yes
  tasks:
- name: Install Nginx
  yum:
  name: Nginx
  state: present
- name: services

## docker --version

docker run ubuntu echo "Hello Pathnex"

FROM ubuntu:20.04
CMD ["Hello", "Hello pathnex"]
