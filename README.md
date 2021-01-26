# Role

Creates an IAM and Role and then Publishes a message onto SNS.

To run, change the values for the **org_name** in *bridgecrew.yml* to be your own.

```yaml
    bridgecrew_account_id: 890234264427
    org_name: james
```

To run:

```shell
$ ansible-playbook bridgecrew.yml
..
```
