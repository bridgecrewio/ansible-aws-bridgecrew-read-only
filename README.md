# Role

Creates an IAM Role and then Publishes a message onto a Bridgecrew SNS topic.

This Ansible playbook is designed to pick up values from an inventory.
In the "default" inventory, change the values for the **org_name**
in *all.yml* to be your own.

```yaml
    org_name:  <your org name>
```

The api token is available from the integrations section of the Bridgecrew platform.
Add it, as an environmental variable:

```bash
export BRIDGECREW_TOKEN= "xxxxxx-xxxxx-xxxx-xxxxxx"
```

And it will be picked up in your Ansible run.

To run:

```shell
$ ansible-playbook bridgecrew.yml -i inventories/default
..
```
