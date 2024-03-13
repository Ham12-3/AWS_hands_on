# AWS_hands_on

# In this section, I created and IAM user using the following steps,

<h1>IAM CREATION</h1>
<p>
  first of all, I went to the IAM section in my root account, then I searched for IAM in my AWS services section, then I checked that IAM is a global service as no region was specified
, afterwards I clicked on User, then create user:
</p>

![aws-1](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/649d851e-74f6-4bb0-8fcf-3752b0497be2)

<hr>

<p>
  Then I created a custom password for myself, then I unclicked the changing of password because it is a demo, but if I want it done real life, I will have to check the changing of password for security purposes.
Then afterwards, I created next and then I created a group called admin and gave it AdministratorAccess so that I can attach the user (abdulhamid to the group)
</p>

![aws-2](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/e68db637-5d7a-41f7-af87-64230fb7f617)

<hr>

<p>
  Then after that, I added tags to the AWS user(department, engineering)
</p>


![aws-3](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/9c797251-2702-4bdf-b11e-891d900739ab)

<hr>
<p>
  Then after the user has been created successfully, I then returned to the users list to show the list of users
</p>

![aws-4](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/2249f4ed-272f-4c13-baae-40ec13b8017c)

<hr>

<p>
  Then after that I created an Alias for the IAM user URL on the IAM dashboard:
</p>

![aws-5](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/e1b3150f-b39c-493d-a0a1-83929e64eb83)

<hr>

![aws-6](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/912b5d24-a1f2-4114-9694-71a32804a078)

<hr>
<p>
  Then voilla, I have logged in into my IAM user account :
</p>


![aws-7](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/d5b3c630-701d-478e-a206-7b27d21ef9b1)

<hr>
<p>
  Process of attaching another policy to the IAM user using the Attach Policy directly section:
</p>



![aws-8](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/65daffb9-a68a-467b-b81f-59826e8da2b3)

<hr>
<p>
  
Then for the policy I have added, here is the JSON form of the policy
</p>

![aws-9](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/87b5da71-888d-48c4-8128-c2a4995ec080)

<hr>

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









