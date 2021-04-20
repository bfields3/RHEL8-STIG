Install Boto via PIP

Install collections

```
ansible-galaxy collection install amazon.aws
ansible-galaxy install RedHatOfficial.rhel8_stig
```

Create vault file with secrets

```
ansible-playbook create_stig.yaml --ask-vault-pass
```
