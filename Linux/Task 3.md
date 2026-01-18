## Task 3: Linux User Setup with Non-Interactive Shell

### :clipboard: To accommodate the backup agent tool's specifications, the system admin team at xFusionCorp Industries requires the creation of a user with a non-interactive shell. Here's your task:
### Create a user named anita with a non-interactive shell on App Server 3.
##### Step 1: Create the required user using the following command.
```
sudo useradd -s /sbin/nologin anita
```
![](https://github.com/amancs1422/KodeKloud-Challenges/blob/239ba94766d7eafe7c33239276ac7d4cbd6147c0/Linux/Images/Task%203_1.jpg)
##### Step 2: Verify the change using the following command.
```
getent passwd anita
```
![](https://github.com/amancs1422/KodeKloud-Challenges/blob/239ba94766d7eafe7c33239276ac7d4cbd6147c0/Linux/Images/Task%203_2.jpg)