# Chapter2

This chapter contains Ansible labs and exercises for Ansible inventories

## Lab Environment

- **Control node:** My laptop (all commands executed locally)
- **Managed nodes:** AWS Linux servers (SSH reachable)
- **Note:** Update inventory files to match *your* environment (IPs, DNS, SSH user, SSH key path).

## Prerequisites
- Ansible installed on your control node
- Control node can access the managed hosts using SSH

## Run playbooks
- clone the repository
```
git clone https://github.com/mohamed-hashicorp/rhce-ansible-automation-study.git
```
- change directory
```
cd rhce-ansible-automation-study/chapter2
```
- Use the inventory 
```
ansible -i inventory all -m ping
```