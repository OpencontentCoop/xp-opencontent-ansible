Ansible playbook
=================


# Role used:
The role are included as submodule in the roles folder, to avoid to manage it with ansible-galaxy
* [epel](https://galaxy.ansible.com/sfromm/epel/)

# How to run playbook
1. Change hosts file
2. Install role dependency
3. Run ansible
```
ansible-playbook -i hosts site.yml
```