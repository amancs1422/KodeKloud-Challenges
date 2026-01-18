## Day 2 : Create Security Group
### :clipboard: The Nautilus DevOps team is strategizing the migration of a portion of their infrastructure to the AWS cloud. Recognizing the scale of this undertaking, they have opted to approach the migration in incremental steps rather than as a single massive transition. To achieve this, they have segmented large tasks into smaller, more manageable units. This granular approach enables the team to execute the migration in gradual phases, ensuring smoother implementation and minimizing disruption to ongoing operations. By breaking down the migration into smaller tasks, the Nautilus DevOps team can systematically progress through each stage, allowing for better control, risk mitigation, and optimization of resources throughout the migration process.<br><br>For this task, create a security group under default VPC with the following requirements:
1. Name of the security group is datacenter-sg.
2. The description must be Security group for Nautilus App Servers
3. Add the inbound rule of type HTTP, with port range of 80. Enter the source CIDR range of 0.0.0.0/0.
4. Add another inbound rule of type SSH, with port range of 22. Enter the source CIDR range of 0.0.0.0/0.
##### Step 1:
![](https://github.com/amancs1422/KodeKloud-Challenges/blob/68f1f9c79ed0795c4ed12954d923a702540c317f/100%20Days%20of%20AWS/Images/Day%202_1.jpg)
##### Step 2:
![](https://github.com/amancs1422/KodeKloud-Challenges/blob/b9ae357186484b44ab2164a87218581940371f99/100%20Days%20of%20AWS/Images/Day%202_2.jpg)
##### Step 3:
![](https://github.com/amancs1422/KodeKloud-Challenges/blob/b9ae357186484b44ab2164a87218581940371f99/100%20Days%20of%20AWS/Images/Day%202_3.jpg)
##### Step 4:
![](https://github.com/amancs1422/KodeKloud-Challenges/blob/b9ae357186484b44ab2164a87218581940371f99/100%20Days%20of%20AWS/Images/Day%202_4.jpg)