This is IaC (Infrastructure as Code) for Magento projects

Prepare ansible by running:
```ansible-galaxy install -r requirements.yml```

This command requires root privileges and installs roles into /etc/ansible/roles.
To install roles in the current directory use next command:
```ansible-galaxy install --roles-path . -r requirements.yml```

How to run Ansible playbook:
```ansible-playbook -i hosts site.yml --vault-password-file=vault.txt```