```bash
sudo apt update
```
```bash
sudo apt install awscli
``
```bash
export AWS_DEFAULT_REGION="ap-southeast-1"
``


```bash
# ec2 volume describe command
aws ec2 describe-volumes --query 'Volumes[].Attachments[].Device' | grep xv | wc -l
```

```bash
# ec2 volume describe with
aws ec2 describe-volumes --query 'Volumes[].Attachments[].Device' | grep /dev/sdh | wc -l
```
```bash
aws ec2 describe-volumes --query 'Volumes[].KmsKeyId' | grep -i mrk-f8c8aeecd74f45ec800d2767d6408519 | wc -l
``

```bash
