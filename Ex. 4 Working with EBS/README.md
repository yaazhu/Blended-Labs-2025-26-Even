[# Lab 3 – Introduction to Amazon Elastic Compute Cloud (EC2)

## Author

* **Name**: Aaron I
* **Register Number**: 212223230002
* **Date of Submission**: 01/05/2026

---

## Objective

The objective of this experiment is to understand the fundamentals of Amazon Elastic Compute Cloud (EC2). This lab focuses on launching and managing a virtual server, understanding instance types and AMIs, connecting to an EC2 instance, monitoring its status, and performing basic instance operations such as start, stop, and terminate.

---

## Prerequisites

* Basic understanding of cloud computing concepts
* AWS account or AWS Academy Lab access
* Web browser with internet connectivity
* Basic knowledge of Linux commands (optional)

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Key Pair
* Security Group
* SSH Client (PuTTY / Terminal)

---

## Tasks Performed

### Task 1: Explore Amazon EC2 Dashboard

Explore the EC2 service dashboard in the AWS Management Console. Observe the different sections such as Instances, AMIs, Instance Types, Key Pairs, Security Groups, and Elastic IPs.

---

### Task 2: Launch an EC2 Instance

Launch a new EC2 instance using Amazon Linux 2 AMI. Select an appropriate instance type (t2.micro) under the free tier. Configure basic settings such as instance name, key pair, and security group.

---

### Task 3: Configure Security Group

Configure a security group to allow inbound access:

* SSH (Port 22) from your IP address
* HTTP (Port 80) from anywhere (0.0.0.0/0)

This security group acts as a firewall for the instance.

---

### Task 4: Connect to EC2 Instance

Connect to the running EC2 instance using SSH. Use the downloaded key pair and connect via terminal or PuTTY.

For Amazon Linux:

```
ssh -i "keyname.pem" ec2-user@<Public-IP>
```

---

### Task 5: Perform Basic Instance Operations

Perform the following operations from the EC2 console:

* Stop the instance
* Start the instance
* Reboot the instance

Observe the state changes of the instance.

---

### Task 6: Monitor EC2 Instance

Monitor the EC2 instance using the Monitoring tab. Observe metrics such as CPU utilization, network in/out, and instance status checks.

---

### Task 7: Terminate EC2 Instance

Terminate the EC2 instance after completing the experiment to avoid unnecessary AWS charges.

---

## Workflow (Student Explanation)


1. Logged in to the AWS Management Console and navigated to the Amazon EC2 Dashboard to explore available services and resources.
2. Launched a new EC2 instance using the Amazon Linux 2 AMI and selected the t2.micro instance type. Created a key pair and configured the necessary instance settings.
3. Configured a security group to allow SSH access on port 22 from my IP address and HTTP access on port 80 from anywhere.
4. Connected to the running EC2 instance using SSH through the terminal with the downloaded key pair. Verified the connection and executed basic Linux commands.
5. Monitored the instance performance using the Monitoring tab, observed CPU and network metrics, performed start, stop, and reboot operations, and finally terminated the instance after completing the experiment.

---

## Output Screenshots (Attach 3)

### Screenshot 1: EC2 Dashboard / Instance List

<img width="1913" height="961" alt="Screenshot 2026-05-29 200406" src="https://github.com/user-attachments/assets/f87bfdd5-c89d-4adb-9a6f-05f408faf35e" />


---

### Screenshot 2: SSH Connection to Instance

<img width="1915" height="952" alt="Screenshot 2026-05-29 200728" src="https://github.com/user-attachments/assets/77ca356a-c9d0-444e-b6a9-7a0697a0fe6a" />



---

### Screenshot 3: Instance Monitoring / Status

<img width="1910" height="976" alt="Screenshot 2026-05-29 202503" src="https://github.com/user-attachments/assets/19a5dbcc-120a-49b5-b9c7-e84d09af70c5" />


---

## Result 

This experiment provided hands-on experience with Amazon EC2 by demonstrating how to launch, connect, manage, and monitor a virtual server in AWS. It helped in understanding the concept of Infrastructure as a Service (IaaS) and how compute resources can be provisioned and controlled on demand in the cloud.
](https://github.com/yaazhu/Blended-Labs-2025-26-Even/edit/main/Ex.%204%20Working%20with%20EBS/README.md)
