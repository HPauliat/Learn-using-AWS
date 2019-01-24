# AWS Project 1 – Connect to internet from a private subnet
# **_CURRENTLY BEING DRAFTED / NOT FINAL VERSION_**

### _Objective :_ Ping google.com from a private subnet

### _AWS Environment expected :_ 1 public subnet 1 and 1 private subnet 2

## **STEPS TO FOLLOW**

### **1. PART 1 : VPC**
#### Manually :
- Create a VPC
- Create the subnets (1 Private, 1 Public)
- Create an Internet Gateway (IGW) for the VPC
- Create a NAT Gateway with an Elastic IP for the Public subnet
- Create/modify Route tables

#### Or Automatically
Choose in « Launch VPC Wizard » (VPC DashBoard) a VPC with Public and Private Subnets
And complete the different steps (see details on manually creation)

### **2. PART 2 : EC2 Instance**
Create a EC2 Instance

### **3. PART 3 : TEST**
- Connect to the instance created
- Try to ping Google.com

## **DETAILS STEP BY STEP**
### **PART 1 : VPC**

**1. Create a VPC :**
Go to Services/VPC, choose the rubrik « Your VPCs » on the left.
Click on « Create VPC » and give a name to the VPC « Exo4LN VPC », for example), 
give an IPv4 adress (10.0.0.0/16) and valid with « Create ».

![Create VPC](file:///C:/Users/hpaul/Pictures/CreateVPC.png)

<IMG SRC="C:/Users/hpaul/Pictures/CreateVPC.png" ALT="Create VPC">
