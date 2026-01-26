# Day 12 : Attach Elastic Network Interface to EC2 Instance.
An instance named “xfusion-ec2” and a volume named “xfusion-volume” already exists in us-east-1 region.
* Attach the “xfusion-volume” volume to the “xfusion-ec2” instance.
* Make sure to set the device name to /dev/sdb while attaching the volume.
## Step 1 : Access the EC2 dashboard in the AWS Management Console.
![](https://github.com/amancs1422/KodeKloud-Challenges/blob/dc61bdab994eaa76c28d06c98c282334af28d1ff/100%20Days%20of%20AWS/Images/Day%2012_1.jpg)
## Step 2 : Find the “xfusion-ec2” EC2 instance to which the “xfusion-volume” volume needs to be attached.
![](https://github.com/amancs1422/KodeKloud-Challenges/blob/dc61bdab994eaa76c28d06c98c282334af28d1ff/100%20Days%20of%20AWS/Images/Day%2012_2.jpg)
## Step 3 : Scroll down to the volume section and find the to be attached “xfusion-volume”.
![](https://github.com/amancs1422/KodeKloud-Challenges/blob/dc61bdab994eaa76c28d06c98c282334af28d1ff/100%20Days%20of%20AWS/Images/Day%2012_3.jpg)
## Step 4 : Select the “xfusion-ec2” EC2 instance and click on "Attach Volume".
![](https://github.com/amancs1422/KodeKloud-Challenges/blob/dc61bdab994eaa76c28d06c98c282334af28d1ff/100%20Days%20of%20AWS/Images/Day%2012_4.jpg)
## Step 5 : Select the “xfusion-volume” from drop-down menu and also select "/dev/sdb" as the device name, then click on "Attach" button.
![](https://github.com/amancs1422/KodeKloud-Challenges/blob/dc61bdab994eaa76c28d06c98c282334af28d1ff/100%20Days%20of%20AWS/Images/Day%2012_5.jpg)
## Step 6 : 
![](https://github.com/amancs1422/KodeKloud-Challenges/blob/dc61bdab994eaa76c28d06c98c282334af28d1ff/100%20Days%20of%20AWS/Images/Day%2012_6.jpg)