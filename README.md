# Ansible SSH wrapper

Handy tools for everyone using ansible for accessing host defined in your inventory.

```
$ ansible-ssh -i inventory -u user [host pattern]
```

ansible-ssh will parse inventory and tries to find host passed as first argument.
It will then execute ssh host.

## Instalation

Just copy ansible-ssh in to your PATH and make it executable. Open ansible-ssh and set inventory_base. 
