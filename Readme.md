# LAMP Stack installation

To install the LAMP stack using ansible, execute following command

```console
git clone https://github.com/thekalpesh7/lamp-stack-ansible.git
set ANSIBLE_HOST_KEY_CHECKING=False
ansible-playbook -i hosts --private-key .ssh/workload_key playbook.yml
```
