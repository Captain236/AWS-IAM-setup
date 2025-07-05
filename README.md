# AWS-IAM-setup
# Introduction
## What is IAM
- **IAM stnds for identity and access management that help us to securely control the aws resources. It allows us to manage users , groups , roles and permissions to define who can access what within your aws environment.**

# Features of IAM

**🔐 1. User Management
You can create, manage, and delete users in your system.
👉 Example: Making accounts for team members in AWS.**

**🛂 Access Control
You decide who can access what in your system.
👉 Example: Give only read access to interns and full access to admins.**

**🧾 Permissions & Policies
You can write rules (called policies) to allow or deny actions.
👉 Example: A rule that says “User A can only view files but not delete them.”**

**👥 Groups
Users can be put into groups to give permissions easily.
👉 Example: A “Developers” group can be allowed to access servers.**

**🆔 Role-Based Access Control (RBAC)
You give roles instead of direct permissions to users.
👉 Example: Assigning a “DatabaseAdmin” role to someone, so they automatically get DB permissions.**

**🔑 Multi-Factor Authentication (MFA)
Adds an extra layer of security using mobile OTP or other devices.
👉 Example: Even if your password is hacked, no one can log in without your phone.**


# What we will do in this project
- **(1) Create users**
- **(2) Create group**
- **(3) Add user to a specific group***
- **(3) Assign permission to a group**

# Let's Begin

## Step 1
- **(1) :- Search for IAM (Manage Access to AWS resource**
![1](https://github.com/user-attachments/assets/0e238e51-7878-42ee-8f51-db5bee45f4e5)

- **(2) :- Click on Users**
![2](https://github.com/user-attachments/assets/32ae1cf6-df2e-4500-9273-48d504d474eb)

- **(3) :- Click on Create Users**
![3](https://github.com/user-attachments/assets/74c665b7-2809-4f10-99fc-e8f0dc807cce)

- **(4) :- Provide a username**
![4](https://github.com/user-attachments/assets/072ba3a7-620d-4257-8b81-afd8b71d2b63)

- **(5) :- Click next after configuration**
# Step 2

- **(1) :- Now Lets create group, Click on create group**
![5](https://github.com/user-attachments/assets/2fea0ff5-71b4-4cfc-add9-72aae60fd028)

- **(2) :- Give your Group name , Then select which permission you want to provide to your group, then click on create group**
![6](https://github.com/user-attachments/assets/c275f59a-6911-457a-bd9c-c2c4d6fa23f1)

- **(3) :- Select your group then click next**
![7](https://github.com/user-attachments/assets/d96c2322-a26a-41d2-aad6-2116eb53d5f1)

- **(4) :- Now Click on create use**
![8](https://github.com/user-attachments/assets/604e0273-ad7d-49fe-bfa1-aabb072318f3)

- **(5) :- Check IAM Dashboard you can see your user and group is created**
![9](https://github.com/user-attachments/assets/3aafb6d7-0f49-4a1c-8d8c-503383a7ec13)

# Step 3

- **(1) :- Lets Login to AWS using your created user, for this click on your created user then , go to Security Credentials & copy the Console Sign-in link , and paste it in incognito tab**
![10](https://github.com/user-attachments/assets/92f156fb-8269-4748-b589-8f62823a4242)

- **(2) :- Now provide your username and password for sign-in
![11](https://github.com/user-attachments/assets/10f6410c-4603-4ef5-99a9-b7f9efe554ed)

- **(3) :- You can see you are login with your created user**
![12](https://github.com/user-attachments/assets/f0fc3468-b4ef-4d43-8ed3-615807baae10)




































