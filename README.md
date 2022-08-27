# What is ECS?
## ECS - Elastic Container Service
### ECS with EC2 Launch
- Launch Docker containers on AWS
- You must provision & maintain the infrastructure (the EC2 instances)
- AWS takes care of starting/Stopping containers
- You can integrate Application Load Balancer

### What is Fargate?
- Launch Docker containers onm AWS
- you do not provision & maintain the infrasctructure (no EC2 instances)
- AWS just runs containers for you based on the CPU/RAM you need

# Hands-on
### Launching a Simple Web Server using ECS Fargate
- Step 1: Create IAM User
Create a User with **ECS Full Access** Policy (Name the User **ecs-course**)

Be sure to check the ConsoleAccess Button and add Password

<img src=https://user-images.githubusercontent.com/86287920/187015274-d552b6ea-3278-4d6f-92b7-5dbfa1328a42.png>

- Step 2: Login using the user that we created

![image](https://user-images.githubusercontent.com/86287920/187015508-dc11e7f7-5dff-443c-818e-aee6faddd071.png)

- Step 3: Go to ECS and Get Started! (https://console.aws.amazon.com/ecs)

![image](https://user-images.githubusercontent.com/86287920/187015634-a05c5448-76e0-476b-b5a0-c73e4776439f.png)
