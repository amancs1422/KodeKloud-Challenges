## Day 2 : Temporary User Setup with Expiry

### :clipboard: As part of the temporary assignment to the Nautilus project, a developer named kareem requires access for a limited duration. To ensure smooth access management, a temporary user account with an expiry date is needed. Here's what you need to do:
#### Create a user named kareem on App Server 2 in Stratos Datacenter. Set the expiry date to 2027-01-28, ensuring the user is created in lowercase as per standard protocol.

#### :bookmark_tabs: Note: You can find the infrastructure details by clicking on the Details of all Users and Servers button on the top-right section of the page.

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