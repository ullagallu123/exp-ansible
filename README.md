# Follow the steps to run these playbook

## db.yaml

```bash
ansible-playbook -i inventory -e "ansible_user=ec2-user -e ansible_password=DevOps321" db.yaml
```

## backend.yaml

```bash
ansible-playbook -i inventory -e "ansible_user=ec2-user -e ansible_password=DevOps321" backend.yaml
```

## forntend.yaml

```bash
ansible-playbook -i inventory -e "ansible_user=ec2-user -e ansible_password=DevOps321" frontend.yaml
```