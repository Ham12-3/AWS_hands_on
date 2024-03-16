


# AWS Hands On

## IAM Creation

First of all, I went to the IAM section in my root account, then I searched for IAM in my AWS services section. Then I checked that IAM is a global service as no region was specified. Afterwards, I clicked on User, then create user.

![aws-1](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/649d851e-74f6-4bb0-8fcf-3752b0497be2)

Then I created a custom password for myself, then I unclicked the changing of password because it is a demo. But if I want it done in real life, I will have to check the changing of password for security purposes. Then afterwards, I created next and then I created a group called admin and gave it AdministratorAccess so that I can attach the user (abdulhamid to the group).

![aws-2](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/e68db637-5d7a-41f7-af87-64230fb7f617)

Then after that, I added tags to the AWS user (department, engineering).

![aws-3](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/9c797251-2702-4bdf-b11e-891d900739ab)

Then after the user has been created successfully, I then returned to the users list to show the list of users.

![aws-4](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/2249f4ed-272f-4c13-baae-40ec13b8017c)

Then after that I created an Alias for the IAM user URL on the IAM dashboard.

![aws-5](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/e1b3150f-b39c-493d-a0a1-83929e64eb83)

![aws-6](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/912b5d24-a1f2-4114-9694-71a32804a078)

Then voilà, I have logged into my IAM user account.

![aws-7](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/d5b3c630-701d-478e-a206-7b27d21ef9b1)

Process of attaching another policy to the IAM user using the Attach Policy directly section.

![aws-8](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/65daffb9-a68a-467b-b81f-59826e8da2b3)

Then for the policy I have added, here is the JSON form of the policy.

![aws-9](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/87b5da71-888d-48c4-8128-c2a4995ec080)

```json
{
    "Version": "2012-10-17",
    "Statement": [
        {
            "Effect": "Allow",
            "Action": "*",
            "Resource": "*"
        }
    ]
}
```

## AWS IAM Security

Access Key already created to add to access the CLI and SDK.

![aws-10](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/4ec11c51-b5a4-4887-8261-600d432ad6db)

The image of how I se the AWS CloudShell 

![aws-11](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/6071a4dc-5f13-4d04-be93-dcb856c0302f)

The process of creating a EC2 IAM role

![aws-12](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/e9490833-454d-4c75-9eec-c7e00ad01578)

Then I configured a trust policy, then a permission policy(access policy)

![aws-13](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/e8ed9858-ea5d-404d-a63f-fdd04fdccf98)


The IAM Credential Report

![aws-14](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/e3d33ae9-0cfc-40b6-a654-6a7b9c1da96b)

The AWS Access Advisor

![aws-15](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/377622d7-9414-4013-97a0-b64b8629a53f)

The AWS low budget I just created:

![aws-16](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/ae8d3a3c-8f7a-4bb9-aeb6-0135abf3797b)


## Amazon EC2

The process of launching an EC2 instance

![aws-17](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/26702b04-eac8-4c2d-b0e6-94ed6dba4083)


![aws-18](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/8990a323-33ef-4df8-9fba-11da8eff0d78)

![aws-19](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/09bd2239-662e-413b-9bdd-336dc0e4fb26)

![aws-20](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/23cd0b61-a2ba-4b90-8d2b-38da96ab0a3b)

![aws-21](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/0ba60f0d-a194-4aa1-91d7-06e76c5ef73d)

![aws-22](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/4dc60203-34e8-4121-aa7e-bc59f88cde67)


Then we run the EC2 and then use it to start a server:
![aws-23](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/20156990-63ca-44b7-bee3-4ebccbb41a7a)



Then we have our security groups and our inbound rules there too:
![aws-24](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/49d5d689-185e-471e-b3ed-3296809d18fa)
![aws-25](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/1176f524-34be-42b4-85a6-3367c853942f)


![aws-26](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/30579343-51da-44e1-a33f-e7eaf7074385)





