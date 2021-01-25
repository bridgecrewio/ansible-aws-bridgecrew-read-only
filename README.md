# Role

Creates an IAM and Role and then Publishes a message onto SNS.

To run, change the values for **ExternalID** and **org_name** in *bridgecrew.yml* to be your own.

```yaml
    ExternalID:  7e935c18-a666-45f8-81bf-2afa672be3b7
    bridgecrew_account_id: 890234264427
    org_name: james
```

To run:

```shell
$ ansible-playbook bridgecrew.yml
```
