
---
 - name: play1
   hosts: localhost
   gather_facts: no
   tasks:
       -  name: create an s3 bucket
          aws_s3:
            ec2_region: us-east-1
            bucket: "test-ansible-bucket-dare123"
            mode: create
            ignore_nonexistent_bucket: True
