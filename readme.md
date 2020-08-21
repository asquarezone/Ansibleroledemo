# This showcases sample role
* For managing different environments create a inventory folder
```bash
ansible-playbook -i inventory/dev appserver.yaml
ansible-playbook -i inventory/qa appserver.yaml
ansible-playbook -i inventory/prod appserver.yaml
```