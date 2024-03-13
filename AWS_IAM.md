# In this section, I created and IAM user using the following steps,

first of all, I went to the IAM section in my root account, then I searched for IAM in my AWS services section, then I checked that IAM is a global service as no region was specified
, afterwards I clicked on User, then create user:
![aws-1](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/649d851e-74f6-4bb0-8fcf-3752b0497be2)

Then I created a custom password for myself, then I unclicked the changing of password because it is a demo, but if I want it done real life, I will have to check the changing of password for security purposes.
Then afterwards, I created next and then I created a group called admin and gave it AdministratorAccess so that I can attach the user (abdulhamid to the group)
![aws-2](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/e68db637-5d7a-41f7-af87-64230fb7f617)


Then after that, I added tags to the AWS user(department, engineering)
![aws-3](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/9c797251-2702-4bdf-b11e-891d900739ab)
Then after the user has been created successfully, I then returned to the users list to show the list of users
![aws-4](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/2249f4ed-272f-4c13-baae-40ec13b8017c)

Then after that I created an Alias for the IAM user URL on the IAM dashboard:
![aws-5](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/e1b3150f-b39c-493d-a0a1-83929e64eb83)


![aws-6](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/912b5d24-a1f2-4114-9694-71a32804a078)


Then voilla, I have logged in into my IAM user account :

![aws-7](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/d5b3c630-701d-478e-a206-7b27d21ef9b1)

Process of attaching another policy to the IAM user using the Attach Policy directly section:

![aws-8](https://github.com/Ham12-3/AWS_hands_on/assets/93613316/65daffb9-a68a-467b-b81f-59826e8da2b3)







