```bash
# ec2 volume describe command
aws ec2 describe-volumes --query 'Volumes[].Attachments[].Device' | grep xv | wc -l
```
