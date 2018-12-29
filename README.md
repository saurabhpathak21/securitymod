#Securitymod

In below space, i will be sharing the best practice and script to lock down the environment if there is any unauthorized access.

Script will list all instances, all security groups and their rules for desired profile

#Before using script, you need to create "profile" file, which is ~/.aws/credentials where you put your AWS keys like this:
# 
``[dev]
aws_access_key_id = *****
aws_secret_access_key = *****
``` 
#.. and then use it in this script

########################################

Steps to create the profile in AWS 

**aws configure   --profile dev
```
AWS Access Key ID [****************G3HA]:
AWS Secret Access Key [****************2n/2]:
Default region name []:
Default output format [None]:
```
