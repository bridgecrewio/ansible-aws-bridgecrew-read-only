# Role

Creates an IAM and Role and then Publishes a message onto SNS.

To run, change the values for the **org_name** in *bridgecrew.yml* to be your own.

```yaml
    api_token: xxxxx-xxxx-xxx-xxx
    org_name:  xxxxxx
```

To run:

```shell
$ ansible-playbook bridgecrew.yml
..
```
