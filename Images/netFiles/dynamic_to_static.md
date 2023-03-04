#### Step1- Once instance created, select the instance and below chose netwrking tab and note down public and private ip address.

![ip](/Images/ip_add.jpg)

#### Step 2: Go to intance state and stop the instance.
and note down the public and private address.
you can see the same private id but public is blank since the instance is stopped.

![stop](/Images/stop.jpg)

##### Step 3: Once instance stopped, select the instance and select networking tab
 and you can see public ip blank but same private ip address.
 ![stop](/Images/stop.jpg)
![stopped](/Images/stopped.jpg)
##### Step 4: Go to Instance state and select start and then check the public ip and private ip.
##### This time the public ip is different.

![restarted](/Images/restart.jpg)

##### So in order to solve this issue we need to allocate elastic ip to public ip.

#### How to allocate elastic id-

##### Step 1:From the EC2 dashboard, navigate to Network and Security on the left navigation and select Elastic IPs.
 Notice that there are no EIPs. Create one by selecting the button Allocate Elastic IP address in the top right. Keep everything as default and hit Allocate. Take note of the EIP address.
![choseelastic](/Images/elastic.jpg)

![allocate](/Images/allocate.jpg)

#### Step 3. Click on allocate button and keep all default setting and click allocate.
![allocate](/Images/allocate1.jpg)
#### Step4
Select the EIP you just created by selecting the checkbox. Now attach this permanent, public IP address to the dynamic instance by navigating to the top right and navigating to Actions and Associate Elastic IP address.

![associate](/Images/associate.jpg)

#### step
Leave the resource type as Instance, and select test instance from the Choose an Instance drop down menu. Under Private IP address, select the empty box. The Private IP associated with that instance is selected. Click the Associate button.

![choseinstance](/Images/choseinstance.jpg)

Now note down the elastic public ip and private ip
