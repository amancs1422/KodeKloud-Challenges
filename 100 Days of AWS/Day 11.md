# Day 11 : Attach Elastic Network Interface to EC2 Instance.
An instance named datacenter-ec2 and an elastic network interface named datacenter-eni already exists in us-east-1 region.
* Attach the datacenter-eni network interface to the datacenter-ec2 instance.
* Make sure status is attached before submitting the task.
* Please make sure instance initialisation has been completed before submitting this task.
## Step 1 : Access the EC2 dashboard in AWS Management Console.
![](https://github.com/amancs1422/KodeKloud-Challenges/blob/4eda5ef59ff39bd0df5014aaaf68b29db45e85bc/100%20Days%20of%20AWS/Images/Day%2011_1.jpg)
## Step 2 : Find the instance to which Elastic Network Interface needs to be attached.
![](https://github.com/amancs1422/KodeKloud-Challenges/blob/4eda5ef59ff39bd0df5014aaaf68b29db45e85bc/100%20Days%20of%20AWS/Images/Day%2011_2.jpg)
## Step 3 : Stop the instance otherwise "Attach Network Interface" option will not be available.
![](https://github.com/amancs1422/KodeKloud-Challenges/blob/4eda5ef59ff39bd0df5014aaaf68b29db45e85bc/100%20Days%20of%20AWS/Images/Day%2011_3.jpg)
## Step 4 : Once the instance is completely stopped click on the "Attach Network Interface" option.
![](https://github.com/amancs1422/KodeKloud-Challenges/blob/4eda5ef59ff39bd0df5014aaaf68b29db45e85bc/100%20Days%20of%20AWS/Images/Day%2011_4.jpg)
## Step 5 : Drop-down and select the VPC and "datacenter-eni" interface, then scroll down and click on attach.
![](https://github.com/amancs1422/KodeKloud-Challenges/blob/4eda5ef59ff39bd0df5014aaaf68b29db45e85bc/100%20Days%20of%20AWS/Images/Day%2011_5.jpg)
## Step 6 : Select the "datacenter-ec2" instance and scroll down to access the "Networking" section.
![](https://github.com/amancs1422/KodeKloud-Challenges/blob/4eda5ef59ff39bd0df5014aaaf68b29db45e85bc/100%20Days%20of%20AWS/Images/Day%2011_6.jpg)
## Step 7 : You will find the "datacenter-eni" interface, scroll to the right.
![](https://github.com/amancs1422/KodeKloud-Challenges/blob/4eda5ef59ff39bd0df5014aaaf68b29db45e85bc/100%20Days%20of%20AWS/Images/Day%2011_7.jpg)
## Step 8 : You will see that the "datacenter-eni" interface is showing "attached" status.
![](https://github.com/amancs1422/KodeKloud-Challenges/blob/4eda5ef59ff39bd0df5014aaaf68b29db45e85bc/100%20Days%20of%20AWS/Images/Day%2011_8.jpg)
## Step 9 : Start the instance and wait for sometime and you will see the 2/2 checks passed which fulfils the last requirement of the lab(Please make sure instance initialisation has been completed before submitting this task).
![](https://github.com/amancs1422/KodeKloud-Challenges/blob/4eda5ef59ff39bd0df5014aaaf68b29db45e85bc/100%20Days%20of%20AWS/Images/Day%2011_9.jpg)

-AK