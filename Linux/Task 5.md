## Task 4: Service User Creation without Home Directory
#### As part of the temporary assignment to the Nautilus project, a developer named mariyam requires access for a limited duration. To ensure smooth access management, a temporary user account with an expiry date is needed. Here's what you need to do:
## :clipboard: Create a user named mariyam on App Server 2 in Stratos Datacenter. Set the expiry date to 2027-04-15, ensuring the user is created in lowercase as per standard protocol.
### Step 1 : Check whether the id already exists in the app server.
```
id mariyam
```
![](https://github.com/amancs1422/KodeKloud-Challenges/blob/820483e04b5e4249905d2ec17053d8a71f642a47/Linux/Images/Task%205_1.jpg)
### Step 2 : Use the following command to create the required user with an expiry date.
```
useradd -e 2027-04-15 mariyam
```
![](https://github.com/amancs1422/KodeKloud-Challenges/blob/820483e04b5e4249905d2ec17053d8a71f642a47/Linux/Images/Task%205_2.jpg)
### Step 3 : Use the following command to validate the change.
```
chage -l mariyam
```
![](https://github.com/amancs1422/KodeKloud-Challenges/blob/820483e04b5e4249905d2ec17053d8a71f642a47/Linux/Images/Task%205_3.jpg)

-AK