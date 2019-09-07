# devops-applike

1. `Vagrantfile` which defined the hardware details of machines.
2. `inventory.ini` which is the inventory of Ansible Playbook.
3. `main.yml` which is the playbook containing IP configs as well.

Run the command:

```shell
$ vagrant up
```
When done, you should be able access `kibana` from http://10.10.10.12 and see the logs.

If you make changes in the playbook, run:

```
$ vagrant provision
```
