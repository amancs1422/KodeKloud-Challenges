## Day 6 : Create a Cron Job
#### The Nautilus system admins team has prepared scripts to automate several day-to-day tasks. They want them to be deployed on all app servers in Stratos DC on a set schedule. Before that they need to test similar functionality with a sample cron job. Therefore, perform the steps below:

### :clipboard: a. Install cronie package on all Nautilus app servers and start crond service.
### :clipboard: b. Add a cron */5 * * * * echo hello > /tmp/cron_text for root user.
## Step 1 : Use the following command to isntall the cronie package.
```
yum install cronie
```
![](https://github.com/amancs1422/KodeKloud-Challenges/blob/ee2cbd744003825ed1ae5e2566d077a26c4aede9/100%20Days%20of%20DevOps/Images/Day%206_1.jpg)
## Step 2 : Check if there are any cron jobs already defined.
```
crontab -l
```
![](https://github.com/amancs1422/KodeKloud-Challenges/blob/ee2cbd744003825ed1ae5e2566d077a26c4aede9/100%20Days%20of%20DevOps/Images/Day%206_2.jpg)
## Step 3 : Check status of crond service. If you see its not running go ahead and restart it.
```
systemctl status crond
```
![](https://github.com/amancs1422/KodeKloud-Challenges/blob/deb433d99fdf8eeda7bd3c1790d72476cd4dfa12/100%20Days%20of%20DevOps/Images/Day%206_3.jpg)
## Step 4 : Use the crontab -e command to add the required cron job and then validate it.
```
crontab -e
```
```
crontab -l
```
![](https://github.com/amancs1422/KodeKloud-Challenges/blob/ee2cbd744003825ed1ae5e2566d077a26c4aede9/100%20Days%20of%20DevOps/Images/Day%206_4.jpg)

-AK