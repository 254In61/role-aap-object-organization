# role-aap-object-credential
Ansible role to build AAP workflow objects

# Ref
https://console.redhat.com/ansible/automation-hub/repo/published/ansible/controller/content/module/schedule/

# How to use

Step 1: Install the role in your environment.
   - You could have roles/requirements.yml if running on AAP.
   - Or simple install on your environment.

Step 2: Define your variables in the structure below

- build: true/false # Bool value to switch role on off.
- organization

Step 3: Call the role from your playbook.

# Example
## vars
example-vars.yml

## playbook
example-playbook.yml

