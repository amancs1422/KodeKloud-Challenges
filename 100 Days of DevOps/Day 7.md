## Day 7 : Linux SSH Authentication
#### The system admins team of xFusionCorp Industries has set up some scripts on jump host that run on regular intervals and perform operations on all app servers in Stratos Datacenter. To make these scripts work properly we need to make sure the thor user on jump host has password-less SSH access to all app servers through their respective sudo users (i.e tony for app server 1).Based on the requirements, perform the following:
### :clipboard: Set up a password-less authentication from user thor on jump host to all app servers through their respective sudo users
## Step 1 : Use the following command to generate the Key Pair.
```
ssh-keygen -t rsa
```
![](https://github.com/amancs1422/KodeKloud-Challenges/blob/ec07e056d722345fe6874ed1d59a438e993ff609/100%20Days%20of%20DevOps/Images/Day%207_1.jpg)
## Step 2 : 
![](https://github.com/amancs1422/KodeKloud-Challenges/blob/ec07e056d722345fe6874ed1d59a438e993ff609/100%20Days%20of%20DevOps/Images/Day%207_2.jpg)
## Step 3 : Copy the key pair to remote servers.
```
ssh-copy-id tony@172.16.238.10
ssh-copy-id steve@172.16.238.11
ssh-copy-id banner@172.16.238.12
```
![](https://github.com/amancs1422/KodeKloud-Challenges/blob/ec07e056d722345fe6874ed1d59a438e993ff609/100%20Days%20of%20DevOps/Images/Day%207_3.jpg)
## Step 4 : Use the following command to validate the password less authentication.
![](https://github.com/amancs1422/KodeKloud-Challenges/blob/ec07e056d722345fe6874ed1d59a438e993ff609/100%20Days%20of%20DevOps/Images/Day%207_4.jpg)

-AK
