# Day 21: Setting Up an EC2 Instance with an Elastic IP for Application Hosting
1. Create an EC2 instance with any AMI type and t2.micro instance type. You can name the instance "nautilus-ec2"
2. Assign an Elastic IP address named "nautilus-eip" to the instance "nautilus-ec2".
## Step 1 : Access the EC2 dashboard in the AWS Management Console.
![](https://github.com/amancs1422/KodeKloud-Challenges/blob/9f50bdc238c3541c39f6a31d7905065dda0b284f/100%20Days%20of%20AWS/Images/Day%2021_1.jpg)
## Step 2 : Click on "Launch Instances" button.
![](https://github.com/amancs1422/KodeKloud-Challenges/blob/9f50bdc238c3541c39f6a31d7905065dda0b284f/100%20Days%20of%20AWS/Images/Day%2021_2.jpg)
## Step 3 : Fill in the name, choose the instance type and click on "Launch Instances" button, the instance will be created.
![](https://github.com/amancs1422/KodeKloud-Challenges/blob/9f50bdc238c3541c39f6a31d7905065dda0b284f/100%20Days%20of%20AWS/Images/Day%2021_3.jpg)
## Step 4 : Goto the "Elastic IPs" section and click on "Associate Elastic IP address" button.
![](https://github.com/amancs1422/KodeKloud-Challenges/blob/9f50bdc238c3541c39f6a31d7905065dda0b284f/100%20Days%20of%20AWS/Images/Day%2021_4.jpg)
## Step 5 : Make sure the region of the Elastic IP is "us-east-1" as per the lab requirement. Then click on "Allocate" button.
![](https://github.com/amancs1422/KodeKloud-Challenges/blob/9f50bdc238c3541c39f6a31d7905065dda0b284f/100%20Days%20of%20AWS/Images/Day%2021_5.jpg)
## Step 6 : Once the EIP is created, change the name and click on "Save" button.
![](https://github.com/amancs1422/KodeKloud-Challenges/blob/9f50bdc238c3541c39f6a31d7905065dda0b284f/100%20Days%20of%20AWS/Images/Day%2021_6.jpg)
## Step 7 : Select the "nautilus-eip" and then click on "Associate Elastic IP address".
![](https://github.com/amancs1422/KodeKloud-Challenges/blob/9f50bdc238c3541c39f6a31d7905065dda0b284f/100%20Days%20of%20AWS/Images/Day%2021_7.jpg)
## Step 8 : Select the "Instance" radio button and then select the "nautilus-ec2" instance, then click on "Associate" button.
![](https://github.com/amancs1422/KodeKloud-Challenges/blob/9f50bdc238c3541c39f6a31d7905065dda0b284f/100%20Days%20of%20AWS/Images/Day%2021_8.jpg)
## Step 9 : 
![](https://github.com/amancs1422/KodeKloud-Challenges/blob/9f50bdc238c3541c39f6a31d7905065dda0b284f/100%20Days%20of%20AWS/Images/Day%2021_9.jpg)

-AK