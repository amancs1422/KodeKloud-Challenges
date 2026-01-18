## Day 2 : Secure root SSH access.

### :clipboard: Following security audits, the xFusionCorp Industries security team has rolled out new protocols, including the restriction of direct root SSH login.
### Your task is to disable direct SSH root login on all app servers within the Stratos Datacenter.

##### Step 1: Check if the id already exists.
```
id kareem
```
##### Step 2: Create the required user with expiry date.
```
sudo useradd -e 2027-01-28 kareem
```
-e prefix is used to setup and expiry date for the user. The format for date to be specified is YYYY-MM-DD.
##### Step 3: To validate the user with expiration date, use the following command.
```
sudo useradd -G nautilus_admin_users stark
```

-AK