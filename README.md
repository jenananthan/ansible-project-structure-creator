#Create structure with default role
- ansible-playbook site.yml   -i inventor

#Create new role to already created directory structure
- ansible-playbook site.yml   -i inventory --tags "create_role" --extra-vars "role=apim"
