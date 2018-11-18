# macbook-playbook

- Install roles
```
$ ansible-galaxy install -p roles -r requirements.yml
```

- Syntax Check
```
$ ansible-playbook playbook.yml -i hosts --syntax-check
```

- Execute
```
$ ansible-playbook playbook.yml -i hosts
```

