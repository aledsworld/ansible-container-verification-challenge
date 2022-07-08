# Conversation App 
An Ansible playbook to pull down config from an end point, and spin up a container with that config. 
Test the container is working 
Clean down the project 

## Requirements
Ansible  
Python3 
docker-py 
 
##Assumptions 
test images are already available in docker 
mock api is already running 

## Run 
'''
ansible-playbook playbook.yaml 
'''