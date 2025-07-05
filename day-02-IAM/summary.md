# 📅 Day 2: IAM (Identity and Access Management)

![IAM image](https://github.com/Prudhvi5442/Daily-AWS-Challenges/blob/9b59934ae77440e37d6b472b158ec03fbb79a433/day-02-IAM/images/AWS-IAM-image.jpg)

## 📘 Topics Covered (Udemy – Section 4)

- What is IAM and why it's critical in AWS
- IAM Users, Groups, and Roles explained
- IAM Policies: Inline vs Managed
- MFA (Multi-Factor Authentication) setup
- IAM Best Practices for secure access
- Permissions boundaries and policy JSON structure
- Hands-on: Creating users, groups, roles, and attaching policies

---

## ✍️ Key Concepts

- **IAM (Identity and Access Management)**: A secure way to control user access to AWS resources.
- **User**: Represents a person or app that interacts with AWS services.
- **Group**: A collection of IAM users that share the same permissions.
- **Role**: Assigned to AWS services or trusted users, used for temporary access.
- **Policy**: A JSON document that defines permissions.
- **MFA**: Adds extra security by requiring two methods of verification.

---

## ✅ Tasks Done

- Created an IAM user with specific permissions
- Assigned the user to a group with managed policies
- Enabled MFA on the user
- Created a custom policy using JSON
- Explored IAM roles and trust relationships

---

### 🎯 IAM User Creation  
![IAM User Creation](https://github.com/Prudhvi5442/Daily-AWS-Challenges/blob/6736301ff6b6165bf39ad71f478b7acb4a454e76/day-02-IAM/images/IAM%201.png)
IAM only readonly access
![IAM User Creation](https://github.com/Prudhvi5442/Daily-AWS-Challenges/blob/6736301ff6b6165bf39ad71f478b7acb4a454e76/day-02-IAM/images/IAM2.png)

### IAM  user groups creation
![user groups creation](https://github.com/Prudhvi5442/Daily-AWS-Challenges/blob/6736301ff6b6165bf39ad71f478b7acb4a454e76/day-02-IAM/images/group.png)
![user groups creation](https://github.com/Prudhvi5442/Daily-AWS-Challenges/blob/6736301ff6b6165bf39ad71f478b7acb4a454e76/day-02-IAM/images/group2.png)

### 🔐 Attached Policies Example  
JSON
![JSON Creation](https://github.com/Prudhvi5442/Daily-AWS-Challenges/blob/6736301ff6b6165bf39ad71f478b7acb4a454e76/day-02-IAM/images/policy-JSON.png)
Virtual
![virtual Creation](https://github.com/Prudhvi5442/Daily-AWS-Challenges/blob/6736301ff6b6165bf39ad71f478b7acb4a454e76/day-02-IAM/images/policy-vitual.png)

### IAM  Roles
![IAM  Roles](https://github.com/Prudhvi5442/Daily-AWS-Challenges/blob/6736301ff6b6165bf39ad71f478b7acb4a454e76/day-02-IAM/images/roles.png)

### 🛡️ MFA Setup  
![MFA Screenshot](https://github.com/Prudhvi5442/Daily-AWS-Challenges/blob/6736301ff6b6165bf39ad71f478b7acb4a454e76/day-02-IAM/images/MFA-1.png)
![MFA Screenshot](https://github.com/Prudhvi5442/Daily-AWS-Challenges/blob/6736301ff6b6165bf39ad71f478b7acb4a454e76/day-02-IAM/images/MFA-2.png)

### IAM Security Tools
Credential report
![Credential report](https://github.com/Prudhvi5442/Daily-AWS-Challenges/blob/6736301ff6b6165bf39ad71f478b7acb4a454e76/day-02-IAM/images/security-tool-1.png)
Last Access
![Last Access](https://github.com/Prudhvi5442/Daily-AWS-Challenges/blob/6736301ff6b6165bf39ad71f478b7acb4a454e76/day-02-IAM/images/tool2.png)

###  



---

## 🧠 Learnings & Reflections

IAM is the foundation of AWS security. It was exciting to manually create users and experiment with policy boundaries and role-based access. Understanding how to restrict permissions at a granular level helped solidify my knowledge of secure AWS design.

---

