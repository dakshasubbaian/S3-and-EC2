# EXP 2:CLOUD-STORAGE-CREATION-S3-AND-LAUNCHING-AN-EC2-INSTANCE-IN-AWS-
## NAME: DAKSHA SUBBAIAN
## REGISTER NUMBER: 212223230036
# Aim
To create a Simple Storage Service (S3) in AWS and to launch an EC2 instance in AWS.  

# Procedure

## a) Steps to Create a First S3 Bucket

1. **Sign in to the AWS Management Console**  
   Go to [AWS S3 Console](https://console.aws.amazon.com/s3).

2. **Open the S3 Service**  
   In the console, type **S3** in the search bar and select **S3** to open the service dashboard.

3. **Create Bucket**  
   Click the **Create bucket** button.

4. **Configure Bucket Settings**  
   - **Bucket name:** Choose a globally unique name.  
   - **AWS Region:** Select the region where you want to store your data.

5. **Object Ownership**  
   Choose between:  
   - **ACLs disabled (recommended):** Bucket owner has full control.  
   - **ACLs enabled:** Control access via access control lists.

6. **Block Public Access Settings**  
   By default, all public access is blocked. Leave it as-is unless you need public access.

7. **Bucket Versioning (optional)**  
   Choose whether to enable versioning for objects in the bucket.

8. **Encryption (optional)**  
   Select encryption options: **SSE-S3**, **SSE-KMS**, or **none**.

9. **Advanced Settings (optional)**  
   Add tags, configure logging, etc.

10. **Create the Bucket**  
    Click **Create bucket** at the bottom of the page.

---

## b) Steps to Launch an EC2 Instance

1. Go to the **EC2 Dashboard** in AWS Console.  
2. Click on **Launch Instance**.  
3. Choose an **Amazon Machine Image (AMI)** (e.g., Amazon Linux).  
4. Select an **instance type** (e.g., `t2.micro` for Free Tier).  
5. Create or choose a **key pair** for SSH access.  
6. Configure **network settings** (use default VPC/subnet).  
7. Configure **storage** (default root volume is fine).  
8. Review the settings and click **Launch Instance**.  
9. Wait for the instance to enter the **running state**.

---

## c) Connect to Your Instance

- **Linux:** Use SSH command with your `.pem` key.  
- **Windows:** Use RDP with decrypted admin password.

---

## d) Steps to Clean Up (Terminate the Instance)

1. Go to **EC2 Instances**.  
2. Select your instance → **Instance State** → **Terminate**.

---

# Snapshots

## Simple Storage Service (S3) 

<img width="1534" height="607" alt="image" src="https://github.com/user-attachments/assets/41206eea-24fe-4625-8692-c77b097a3787" />



## EC2 (Elastic Compute Cloud) – Instance  
<img width="961" height="701" alt="image" src="https://github.com/user-attachments/assets/20a2d1f0-dd33-4348-9cdc-d1157c83eb78" />

<img width="969" height="709" alt="image" src="https://github.com/user-attachments/assets/85e55516-4f7b-4d50-85be-3258ad52639c" />



# Result
Thus, a Simple Storage Service (S3) and EC2 (Elastic Compute Cloud) instance has been successfully created and launched in AWS.
