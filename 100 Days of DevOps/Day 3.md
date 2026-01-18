## Day 2 : Secure root SSH access.

### :clipboard: Following security audits, the xFusionCorp Industries security team has rolled out new protocols, including the restriction of direct root SSH login.
### Your task is to disable direct SSH root login on all app servers within the Stratos Datacenter.

#### Step 1: Edit the sshd service config file to remove the PermitRootLogin permission.
![](https://github.com/amancs1422/KodeKloud-Challenges/blob/master/100%20Days%20of%20DevOps/Images/Day%203_1.jpg)
```
sudo vi /etc/ssh/sshd_config
```
![](https://github.com/amancs1422/KodeKloud-Challenges/blob/master/100%20Days%20of%20DevOps/Images/Day%203_3.jpg)
![](https://github.com/amancs1422/KodeKloud-Challenges/blob/master/100%20Days%20of%20DevOps/Images/Day%203_2.jpg)
![]ps://github.com/amancs1422/KodeKloud-Challenges/blob/master/100%20Days%20of%20DevOps/Images/Day%203_4.jpg)
#### Step 2: Restart sshd service.
```
sudo systemctl sshd
```
![](https://github.com/amancs1422/KodeKloud-Challenges/blob/master/100%20Days%20of%20DevOps/Images/Day%203_5.jpg)

-AK