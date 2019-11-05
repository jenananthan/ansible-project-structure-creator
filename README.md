# ansible-project-structure-creator
Ansible best practices documentation suggests two directory structures 
1. Directory Layout (https://docs.ansible.com/ansible/latest/user_guide/playbooks_best_practices.html#directory-layout)
2. Alternative Directory Layout (https://docs.ansible.com/ansible/latest/user_guide/playbooks_best_practices.html#alternative-directory-layout)

This project is created using  ansible to create the directory layouts suggested in above documentations.

# How to use

## Create Directory Layout
1. Clone the project
2. Update the project name and other configuration values in ansible-project-structure-creator/host_vars/controlmachine.yml
3. Execute the below command

```sh
ansible-playbook site.yml   -i inventory
```

## Create Alternative Directory Layout
1. Clone the project
2. Update the project name and other configuration values in ansible-project-structure-creator/host_vars/controlmachine.yml
3. Execute the below command

```sh
ansible-playbook site.yml -i inventory  --extra-vars "p=2"
```
