# 🔐 Securing Application Credentials with AWS Secrets Manager

This project demonstrates how to securely store, retrieve, and rotate sensitive application credentials using **AWS Secrets Manager**, **Amazon RDS**, and **Amazon EC2**.

---

## 📌 Lab Objectives

- Store credentials securely in AWS Secrets Manager
- Retrieve and view secrets securely
- Connect to Amazon RDS using secrets
- Rotate secrets manually via the AWS Console
- Practice secure credential management for cloud-based applications

---

## 🧰 AWS Services Used

- **AWS Secrets Manager** – to store and manage secrets
- **Amazon RDS** – as a sample database using MySQL
- **Amazon EC2** – to connect and interact with the RDS instance
- **AWS Key Management Service (KMS)** – for secret encryption

---

## 🖼️ Screenshots & Descriptions

### 1. 💻 EC2 Instance Connected via Session Manager
![Screenshot (11)](https://github.com/user-attachments/assets/53616f8f-6572-4699-803f-afb8afb83400)
![Screenshot (12)](https://github.com/user-attachments/assets/cf63e0cb-7699-402a-a377-aad4595b9fa6)
![Screenshot (13)](https://github.com/user-attachments/assets/b0359f2e-34c3-40a2-8a12-fb7bf29f718b)

> Shows a terminal connection to an EC2 instance via AWS Session Manager, used for installing MySQL/MariaDB client and running queries.

### Basic Architecture of the Project Environment
![image](https://github.com/user-attachments/assets/691c66b7-1682-4c88-ad8c-bfc514d19a39)


### 2. 🔁 Manual Secret Rotation and versions
![Screenshot (15)](https://github.com/user-attachments/assets/cb4256e2-91d9-4525-899d-9c76a39732d4)

![Screenshot (14)](https://github.com/user-attachments/assets/a8622897-4cdd-4d80-b0ac-f9657eca188e)

> Demonstrates how to manually rotate secrets via the AWS Console—a critical step in simulating a real-world security scenario.

Diagram
![d3d82083-4d91-4955-9177-3cbe2bcca102](https://github.com/user-attachments/assets/74e27d09-3fe8-4401-b7af-f3f4a24271d5)


## 🧠 Key Learnings

- Secrets should **never be hardcoded** in applications.
- AWS Secrets Manager provides a centralized, secure place for sensitive credentials.
- Combining **Secrets Manager**, **RDS**, and **EC2** shows how modern applications access protected data without exposing secrets.
- Manual and automatic **rotation of secrets** are essential for security hygiene.

## 📣 Author

**Amarachi Emeziem**  
Cloud Security Enthusiast | AWS Certified | CompTIA Security+ (in progress)

Let's connect: https://www.linkedin.com/in/amarachilemeziem/ 🚀

