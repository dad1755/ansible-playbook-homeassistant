# ansible-playbook-homeassistant

THIS ANSIBLE CODE TO INSTALL HOME ASSISTANT TO YOUR VIRTUAL BOX.

X NO DOCKER
X NO SUPERVISOR

This Ansible playbook automates the installation of Home Assistant Core on Linux, setting up dependencies, configuring Python 3.12, and preparing the system for smart home automation. It requires minimal manual intervention, making it easy to customize and run Home Assistant efficiently.

Replace hosts: xxx.xxx.xxx.xxx with your target IP

- name: Install Home Assistant Core on Linux
  hosts: 192.168.204.97
  become: yes
