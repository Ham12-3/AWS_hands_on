


# AWS Hands On

## IAM Creation

1. Go to the IAM section in the root account.
2. Search for IAM in the AWS services section.
3. Check that IAM is a global service.
4. Click on "User" and then "Create User".

![aws-1](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/649d851e-74f6-4bb0-8fcf-3752b0497be2)

5. Create a custom password and uncheck "Require password change" (for demo purposes).
6. Click "Next" and create a group called "admin" with AdministratorAccess.
7. Add tags to the AWS user (e.g., department, engineering).

![aws-2](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/e68db637-5d7a-41f7-af87-64230fb7f617)
![aws-3](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/9c797251-2702-4bdf-b11e-891d900739ab)

8. After successful user creation, return to the users list.

![aws-4](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/2249f4ed-272f-4c13-baae-40ec13b8017c)

9. Create an Alias for the IAM user URL on the IAM dashboard.

![aws-5](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/e1b3150f-b39c-493d-a0a1-83929e64eb83)
![aws-6](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/912b5d24-a1f2-4114-9694-71a32804a078)

10. Log into the IAM user account.

![aws-7](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/d5b3c630-701d-478e-a206-7b27d21ef9b1)

11. Attach another policy to the IAM user using the "Attach Policy" section.

![aws-8](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/65daffb9-a68a-467b-b81f-59826e8da2b3)

12. JSON form of the policy:

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

- Access Key creation for CLI and SDK.

![aws-10](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/4ec11c51-b5a4-4887-8261-600d432ad6db)

- Using AWS CloudShell.

![aws-11](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/6071a4dc-5f13-4d04-be93-dcb856c0302f)

- Creating an EC2 IAM role.

![aws-12](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/e9490833-454d-4c75-9eec-c7e00ad01578)

- Configuring trust and permission policies.

![aws-13](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/e8ed9858-ea5d-404d-a63f-fdd04fdccf98)

- IAM Credential Report.

![aws-14](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/e3d33ae9-0cfc-40b6-a654-6a7b9c1da96b)

- AWS Access Advisor.

![aws-15](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/377622d7-9414-4013-97a0-b64b8629a53f)

- AWS low budget created.

![aws-16](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/ae8d3a3c-8f7a-4bb9-aeb6-0135abf3797b)

## Amazon EC2

- Launching an EC2 instance.

![aws-17](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/26702b04-eac8-4c2d-b0e6-94ed6dba4083)
![aws-18](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/8990a323-33ef-4df8-9fba-11da8eff0d78)
![aws-19](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/09bd2239-662e-413b-9bdd-336dc0e4fb26)
![aws-20](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/23cd0b61-a2ba-4b90-8d2b-38da96ab0a3b)
![aws-21](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/0ba60f0d-a194-4aa1-91d7-06e76c5ef73d)
![aws-22](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/4dc60203-34e8-4121-aa7e-bc59f88cde67)

- Running the EC2 and starting a server.

![aws-23](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/20156990-63ca-44b7-bee3-4ebccbb41a7a)

- Security groups and inbound rules.

![aws-24](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/49d5d689-185e-471e-b3ed-3296809d18fa)
![aws-25](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/1176f524-34be-42b4-85a6-3367c853942f)
![aws-26](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/30579343-51da-44e1-a33f-e7eaf7074385)
![aws-27](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/7535e6b3-60a0-46bd-93c2-544aad982045)

- Accessing EC2 instance with SSH on Windows PowerShell.

![aws-28](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/b8f572cf-2ccc-47af-9639-43aa4b4e8024)

- Using EC2 Instance Connect.

![aws-29](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/3723f404-2f16-4c84-b45b-07aba04f813a)


