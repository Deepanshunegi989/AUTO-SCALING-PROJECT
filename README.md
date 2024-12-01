# AUTO-SCALING-PROJECT
creating auto scaling group in AWS 

# Auto Scaling Project

This project demonstrates the creation and configuration of an Auto Scaling setup in AWS to maintain high availability and scalability for applications. The setup includes the creation of a launch template and an Auto Scaling Group (ASG) with a minimum of three EC2 instances.

## Features

- *Launch Template: A reusable template for launching EC2 instances. The template is named **t-1*.
- *Auto Scaling Group (ASG): Automatically manages the number of EC2 instances based on the desired configuration. The group is named **as*.
- *Minimum Instances: Ensures that a minimum of **3 instances* are always running to maintain system reliability.
- *High Availability*: The system can scale out (add instances) or scale in (remove instances) based on demand.

## Project Configuration

1. *Launch Template (t-1)*:
   - Predefined configurations for launching instances.
   - Includes details such as instance type, AMI, key pair, security groups, and more.

2. *Auto Scaling Group (as)*:
   - Minimum number of instances: *3*.
   - Automatically creates and terminates EC2 instances based on policies and conditions.
   - Distributes instances across multiple Availability Zones for fault tolerance.

3. *Scaling Policy* (Optional):
   - Configurable to scale instances dynamically based on CPU utilization, network traffic, or other metrics.

## How It Works

1. *Launch Template Creation*:
   - Created a launch template named *t-1* to define the configuration for EC2 instances.

2. *Auto Scaling Group Setup*:
   - Created an Auto Scaling Group named *as* with a minimum instance count of *3*.

3. *Instance Deployment*:
   - Upon creation, three instances were launched automatically by the Auto Scaling Group.

4. *Scaling Behavior*:
   - If the system detects higher demand, new instances will be launched automatically.
   - If demand decreases, excess instances will be terminated while maintaining the minimum count.

## Usage

1. Clone the repository or integrate the setup into your AWS environment.
2. Use the AWS Management Console, CLI, or SDKs to monitor the Auto Scaling Group and modify settings as needed.

## Prerequisites

- An AWS account with necessary permissions.
- Basic understanding of EC2, Auto Scaling, and Launch Templates.
- Pre-configured security groups, AMI, and key pairs.

## Benefits

- *Scalability*: Automatically adjusts resources to meet workload demands.
- *Cost Efficiency*: Optimizes resource usage, saving costs by scaling in during low-demand periods.
- *Reliability*: Ensures a minimum number of instances are always running.

---

### Notes

- This setup is a foundational example and can be extended with advanced features like dynamic scaling policies, custom AMIs, and load balancers.
- Ensure proper monitoring and alerts are configured for effective management.

---

## Author

*Deepanshu Singh Negi*  
AWS | Linux | CCNA | Networking  
