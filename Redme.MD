https://docs.ansible.com/ansible/latest/playbook_guide/playbooks_tags.html

# ansible-valut help to product the data inside the yaml file

to create a secure file # ansible-vault create <file_name>
to edit the file        # ansible-vault edit <file_name>
to reset the oldkey     # ansible-vault rekey <file_name>
ansible-vault decrypt <file_name>

provide password in file (first)

ansible-vault create --vault-id  first v3.yaml
ansible-vault encrypt --vault-password-file first v3
ansible-vault edit --vault-password-file first v3
ansible-vault decrypt --vault-password-file first v3



https://docs.ansible.com/ansible/latest/cli/ansible-playbook.html#cmdoption-ansible-playbook-vault-password-file


ansible-vault encrypt --vault-password-file first v3


ansible.cfg  
hosts 
group_vars  
host_vars               
tomcat.service.j2       # template
tomcat-users.xml.j2     # template
context.xml  		# file 
tomcat.yaml
  vars			# vars
  task			# task main.yaml
  handlers		# main.yaml


