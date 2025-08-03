
# 🌐 Cloud Internship – CodTech IT Solutions

## 📋 Internship Overview
This is a **8-week Cloud Computing Internship** offered by **CodTech IT Solutions**, focused on building hands-on skills in cloud platforms such as **AWS** and **Google Cloud**. The internship includes weekly tasks to gain practical experience with real-world cloud infrastructure and services.

---

## ☁️ Task 1: Cloud Storage Setup on AWS S3

### ✅ Task Summary:
- Created and configured an **S3 bucket** on AWS.
- Uploaded sample files to the bucket.
- Set up **public read access** using a custom bucket policy.

This task helped build foundational knowledge of cloud storage management and access control in AWS.


## ☁️ Task 2: Cloud Monitoring and Alerts (AWS CloudWatch)

### ✅ Task Summary:
- Set up **monitoring and alerting** for a cloud-based application using **AWS CloudWatch**.
- Created **CPU Utilization alarms** for an EC2 instance with:
  - 1-minute evaluation period
  - Threshold-based condition
  - Email notification setup and confirmation
- Designed and configured a **custom CloudWatch Dashboard** displaying real-time metrics using widgets like line, bar, and number graphs.

This task provided hands-on experience with performance tracking and alert automation in AWS, crucial for maintaining cloud infrastructure visibility.


## ☁️ Task 3: Multi-Cloud Architecture

### ✅ Task Summary:
- Designed and implemented a **multi-cloud architecture** by integrating services across **AWS** and **Microsoft Azure**.
- Created a Linux EC2 instance on AWS and configured full network access.
- Set up a **Resource Group** and used **Azure Arc** to connect the AWS instance to Azure.
- Executed and verified the connection script from AWS to Azure using `azure.sh`, enabling **interoperability** between the two platforms.
- Successfully demonstrated that the same server can be managed from both cloud providers.

This task highlighted the potential of hybrid and multi-cloud strategies in managing distributed cloud resources.


## 🔐 Task 4: Cloud Security Implementation on AWS

### ✅ Task Summary
- Created two **EC2 instances**: one tagged as **Production**, the other as **Development**.
- Implemented a custom **IAM policy** to restrict user actions based on resource tags.
- Denied permissions for actions like `StopInstance`, `CreateTags`, and `DeleteTags`.
- Created an **IAM alias user** and a **user group** with the new policy attached.
- Verified policy restrictions via **IAM Policy Simulator** and manual testing.

This task enhanced my understanding of **Identity and Access Management (IAM)** in cloud environments and how fine-grained permissions improve cloud security.




