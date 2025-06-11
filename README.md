# 🛠️ AWS EC2 Web Server Setup with Custom VPC

This project walks through setting up an EC2 instance inside a custom VPC on AWS, including all necessary networking components. The EC2 instance runs a basic web server and is accessible over the internet.

---

## ✅ Steps

### 1. Creating Key Pair  
![Step 1 - Key Pair](https://github.com/user-attachments/assets/c5cd4860-dc35-42fa-8949-3084777b1ddb)
)

---

### 2. Creating the VPC  
![Step 2 - VPC](https://github.com/mayurminfy1/AWS-assignment/blob/main/my-vpc.png?raw=true)

---

### 3. Creating Subnets  
![Step 3 - Subnet](https://github.com/mayurminfy1/AWS-assignment/blob/main/public-subnet.png?raw=true)

---

### 4. Creating Internet Gateway  
![Step 4 - IGW](https://github.com/mayurminfy1/AWS-assignment/blob/main/internet-gateway.png?raw=true)

---

### 5. Configuring Public Route Table and Security Group  
- **Route Table:**  
  ![Step 5 - Route Table](https://github.com/mayurminfy1/AWS-assignment/blob/main/route-table.png?raw=true)



---

### 6. Launching EC2 Instance  
![Step 6 - Launch EC2](https://github.com/mayurminfy1/AWS-assignment/blob/main/ec2-instance.png?raw=true)

---

### 7. Testing the Web Server  
Visit the public IPv4 address of your EC2 instance in a browser.  


![Step 7 - Web Server Test](https://github.com/mayurminfy1/AWS-assignment/blob/main/result.png?raw=true)

---

## 🧹 Cleanup

To avoid incurring costs on your AWS account, follow these cleanup steps:

1. **Terminate EC2 Instance**
   - Go to EC2 → Instances → Select your instance → Actions → Terminate

2. **Delete Key Pair**
   - EC2 → Key Pairs → Select and delete your key

3. **Delete Security Group**
   - EC2 → Security Groups → Select your custom group → Delete

4. **Detach and Delete Internet Gateway**
   - VPC → Internet Gateways → Detach from VPC → Delete

5. **Delete Route Table**
   - VPC → Route Tables → Select your custom table → Delete

6. **Delete Subnet**
   - VPC → Subnets → Select and delete

7. **Delete VPC**
   - VPC → Your VPCs → Select your custom VPC → Delete
  
     ![Step 8 - Cleanup](https://github.com/mayurminfy1/AWS-assignment/blob/main/cleanup.png?raw=true)

---





