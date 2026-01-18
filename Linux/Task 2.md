## Task 2 : Group Creation and User Assignment :family:

### :clipboard: The system admin team at xFusionCorp Industries has streamlined access management by implementing group-based access control. Here's what you need to do:
##### a. Create a group named nautilus_admin_users across all App servers within the Stratos Datacenter.
##### b. Add the user stark into the nautilus_admin_users group on all App servers. If the user doesn't exist, create it as well.

#### :bookmark_tabs: Note: You can find the infrastructure details by clicking on the Details of all Users and Servers button on the top-right section of the page.

##### Step 1: Check if the id already exists.
```
id stark
```
![](https://github.com/amancs1422/KodeKloud-Challenges/blob/d0b35affb531022a4622a35804915d65efb40e8a/Linux/Images/Task%202_1.jpg)
##### Step 2: Create the required group.
```
sudo groupadd nautilus_admin_users
```
##### Step 3: Create and add the user to the group created.
```
sudo useradd -G nautilus_admin_users stark
```
![](https://github.com/amancs1422/KodeKloud-Challenges/blob/d0b35affb531022a4622a35804915d65efb40e8a/Linux/Images/Task%202_2.jpg)
##### Step 4: Repeat same steps on all three app servers.

-AK