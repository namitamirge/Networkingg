#### This md files have detail information about lab2 execution
Problem: When ec2 user start or stop the public instance, the public IP address changes time to time.
User wants static public IP address as he/she doesn't want to keep instance running continously.
Below are the steps with screenshots of every step to change ec2 instance dynamic public ip address into static ip address
#### Step 1: Run the lab and click on AWS

##### Step 2 : Select instance and launch new instance
![launch](/Images/launch.jpg)



##### Step 3: Add tag key-Name and value- test3-instance

![tag](/Images/add%20tag.jpg)



##### Step4: Select t3.micro and vockey key value pair
![t3](/Images/t3.jpg)
 
 #### Step5: Network setting -Edit network setting and 
 Network: Choose vpc-xxxxxxxx | Lab VPC
Subnet: Choose subnet-xxxxxx | Public Subnet 1
Auto-assign Public IP: Set to enable

![network_setting](/Images/network_setting.jpg)
#### Step6: Under storage section keep storage default

#### Step 7: Configure Security Group: 

Under Assign a security group, select the Select an existing security group radio button and select the security group with the name Linux Instance SG. Then navigate to the bottom of the window and hit Review and Launch.
![security_groyup](/Images/security_group.jpg)
#### Step 8: Review Instance Launch:

Navigate to the bottom of the window and hit Launch.

