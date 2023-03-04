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

##### So in order to solve this issue we need to allocate elastic ip to public ip.

