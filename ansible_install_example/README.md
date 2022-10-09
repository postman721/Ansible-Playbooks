This a Debian package install example via Ansible. This playbook will try to install nano and vim.

Usage: ansible-playbook setupbook.yml -i inventory --ask-pass

Notice:   

Setupbook.y,l looks python from /usr/bin/python:

vars:
      ansible_python_interpreter: /usr/bin/python

Customize vars python value from setupbook.yml if needed.
