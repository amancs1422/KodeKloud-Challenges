## Day 5: SElinux Installation and Configuration
### The xFusionCorp Industries security team recently did a security audit of their infrastructure and came up with ideas to improve the application and server security. They decided to use SElinux for an additional security layer. They are still planning how they will implement it; however, they have decided to start testing with app servers, so based on the recommendations they have the following requirements:
## :clipboard: Install the required packages of SElinux on App server 3 in Stratos Datacenter and disable it permanently for now; it will be enabled after making some required configuration changes on this host. Don't worry about rebooting the server as there is already a reboot scheduled for tonight's maintenance window. Also ignore the status of SElinux command line right now; the final status after reboot should be disabled.
## Step 1 : To install SELinux use the following command:
```
sudo yum install policycoreutils selinux-policy selinux-policy-targeted libselinux-utils setroubleshoot-server setools setools-console mcstrans
```
## Step 2 : Edit the /etc/selinux/config file to make the following changes.
SELINUX=disabled
SELINUXTYPE=targeted
## Step 3 : The following command will show you the SELINUX=disabled value.
```
sestatus
```

-AK