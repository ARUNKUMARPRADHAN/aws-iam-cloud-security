# aws-iam-cloud-security
A project demonstrating AWS IAM roles, users, groups, policies, and tag-based access control

# Cloud Security with AWS IAM

## 📌 Overview
This project showcases how AWS IAM (Identity and Access Management) can be used to implement fine-grained access control across EC2 environments based on tagging.

## 🔧 Key Actions
- Created IAM users and user groups
- Developed and attached JSON-based IAM policies to restrict/allow EC2 actions
- Used environment tags like `Env=production` and `Env=development` for policy scoping
- Created an account alias for simplified console login

## 🔐 Policy Features
- Allow full control over EC2 instances tagged with `Env=development`
- Deny tag creation/deletion across all instances
- Prevent unauthorized actions on production instances

## 🧪 Testing
- Verified restricted access for production instances (`Access Denied`)
- Confirmed allowed actions on development instances (`Access Granted`)

## 📝 Report
See full documentation in [legendary-aws-security-iam.pdf](./legendary-aws-security-iam.pdf)

---

**Created by:** Arun Kumar  
**Submitted to:** NextWork.org
