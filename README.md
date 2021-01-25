# Role

Creates an IAM and Role and then Publishes a message onto SNS:

```bash
aws sns publish --topic-arn arn:aws:sns:eu-west-1:890234264427:handle-customer-actions --message file://message.json  -
```