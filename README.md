# Overview
This project is intended to be a starting point for those new to Tower. It is intended to demonstrate how it's components are part of a functional workflow for automation and managment using Ansible. This includes the following tasks
* A basic directory structure for playbooks and the roles used by those playbooks
* (commented) examples. Users are encouraged to dig into the files and read the comments to understand how things work
* A site.yml that includes the equivelent of a hello_world. In this case printing out debug messages about the running job
* Skeleton playbooks for patching RHEL and/or Windows Servers. 
* Skeleton vault files to be encrypted by the user using ansible-vault
* TODO: create a bootstrap playbook to create the Project, Job Templates, Credentials, etc

# Getting Started
Until the bootstrap playbook is done you should be able to do the following. 
* Fork this repo and add as a project. 
* Create a Job Template that uses this site.yml, existing credentials, existing inventory,
- if you are familiar with ansible, you can create a Patching Job template from server_patching.yml. Word of caution, the clients will be patched and rebooted if necessary.
* Run the job and see debug information printed for all hosts in the inventory

