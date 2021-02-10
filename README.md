# Role

Creates an IAM and Role and then Publishes a message onto SNS.

This Ansible playbook is designed to pick up values from an inventory.
In the "default" inventory, change the values for the **org_name**
and **api_token** in *all.yml* to be your own.

The api_token is available from the integrations section of the Bridgecrew platform.

```yaml
    api_token: <your-token>
    org_name:  <your org name>
```

To run:

```shell
$ ansible-playbook bridgecrew.yml -i inventories/default
..
```
