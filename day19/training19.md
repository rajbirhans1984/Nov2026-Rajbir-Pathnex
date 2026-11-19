# Day -19 - Training

## Ansible Install Nginx on codefly Server

---

- name: Install Nginx on codefly server
  hosts: all
  become: yes

  tasks:
  - name: Install Nginx
    yum:
    name: Nginx
    state: present

# Docker --version

docker run ubuntu echo "Hello Codefly"

FROM ubuntu:20.04
CMD ["echo", "Hello Codefly"]
