## Day 4: Script Execution Permissions
### In a bid to automate backup processes, the xFusionCorp Industries sysadmin team has developed a new bash script named xfusioncorp.sh. While the script has been distributed to all necessary servers, it lacks executable permissions on App Server 3 within the Stratos Datacenter.
### :clipboard: Your task is to grant executable permissions to the /tmp/xfusioncorp.sh script on App Server 3. Additionally, ensure that all users have the capability to execute it.
#### Step 1: Checkout what the current permissions for the script file are.
```
ls -ltr /tmp
```
![](https://github.com/amancs1422/KodeKloud-Challenges/blob/fdd793f1484f408fc14d14afeadae97b34d667fd/100%20Days%20of%20DevOps/Images/Day%204_1.jpg)
#### Step 2: Change the script permission using the following command.
```
sudo chmod 755 /tmp/xfusioncorp.sh
```
![](https://github.com/amancs1422/KodeKloud-Challenges/blob/d868eff26d9d50cdd5f274104c6174f923355c4d/100%20Days%20of%20DevOps/Images/Day%204_2.jpg)
#### Step 3: Verify that the permission changes have been made.
```
ls -ltr /tmp
```
![](https://github.com/amancs1422/KodeKloud-Challenges/blob/fdd793f1484f408fc14d14afeadae97b34d667fd/100%20Days%20of%20DevOps/Images/Day%204_3.jpg)

Note: Here the following commands will not work(tried and failed), because the lab validator is looking for all users to have read and execute permissions.