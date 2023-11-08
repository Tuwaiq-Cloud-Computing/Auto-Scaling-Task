# Auto-Scaling-Task

### Task 1: Create a VPC:

Create a VPC name it (project-xyz) in Riyadh Region, make sure the IPv4 CIDR Block you choose can have only (256) subnet and each subnet can have (256) IP

### Task 2: Create a VSwitch:

A two (VSwitch) is a subnet within your VPC. You can create multiple VSwitches within a VPC to segment your network.

- Create a subnet in Zone A and name it (project-xyz-a)
- Create a subnet in Zone B and name it (project-xyz-b)
  
### Task 3: Create a ECS:
Create ESC Instance using centos 7.9 image and use the commands below in User Data field:
```
#!/bin/bash
yum install stress
stress -c 100 -t 500&
```

### Task 4: Auto Scaling Group Setup:

- Create an Auto Scaling Group and build your scaling configuration.

### Task 5: Create 2  scaling rules for 2 event-triggered task:

- Scale Out (Add 1 Instances)
- Scale In (Remove 1 Instances)




