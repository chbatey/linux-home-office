Used to configure my Fedora laptop and desktop but shoud work with any Yum based system

To run:

```
./boostrap
ansible-playbook -i hosts fedora.yml --ask-sudo-pass
```