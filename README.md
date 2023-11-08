# Auto-Scaling-Task

### Task 1: Create a VPC:
- Create a VPC name it (scaling-project) .

### Task 2: Create a VSwitch:
- Create 2 VSwitch in 2 Different Availability Zones
  
### Task 3: Create a ECS Instance:
Create ESC Instance using centos 7.9 image and use the commands below in User Data field:
```
#!/bin/bash
yum install stress -y
stress -c 100 -t 500&
```

### Task 4: Auto Scaling Group Setup:

- Create an Auto Scaling Group and build your scaling configuration.

### Task 5: Create 2  scaling rules for 2 event-triggered task:

- Scale Out (Add 1 Instances)
- Scale In (Remove 1 Instances)

## Submission:

- After finishing the tasks take screen shot of Scaling task .
- take screen shot of Scaling activity .
- Then upload the pictures to the forked repo and then create a pull request.





