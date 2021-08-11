# ansible

# aws-s3-deploy
### Before starting deployment we will need to add credentials

```bash
   export AWS_ACCESS_KEY_ID="xxxxx"
   export AWS_SECRET_ACCESS_KEY="xxxxxxx"
```

### In aws you must have mentioned permissions

- AmazonVPCReadOnlyAccess
- AmazonEC2ReadOnlyAccess
- ElasticLoadBalancingReadOnly
- AmazonRDSReadOnlyAccess
- AmazonS3ReadOnlyAccess


### Commands
```bash 
    ansible-playbook -i inventory playbook.yml
```    
