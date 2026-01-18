## Day 2 : Secure root SSH access.

### :clipboard: Following security audits, the xFusionCorp Industries security team has rolled out new protocols, including the restriction of direct root SSH login.
### Your task is to disable direct SSH root login on all app servers within the Stratos Datacenter.

#### Step 1: Edit the sshd service config file to remove the PermitRootLogin permission.
```
sudo vi /etc/ssh/sshd_config
```
![]()
#### Step 2: Restart sshd service.
```
sudo systemctl sshd
```
![]()

-AK