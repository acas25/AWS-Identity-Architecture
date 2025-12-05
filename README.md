# AWS Identity Architecture — Complete Knowledgebase

This repository is a comprehensive, 18-page deep-dive into the identity, access, and authorization model of AWS.  
It covers every layer of the identity stack, including IAM, STS, Organizations, SCPs, workload identities, data services, network control planes, and complete end-to-end architectural blueprints.

All pages are fully documented with long-form explanations and Mermaid diagrams compatible with GitHub's Markdown renderer.

---

## 📚 Table of Contents

### **Core Identity Concepts**
1. [IAM Foundations](wiki/Page-01-IAM-Foundations.md)  
2. [Amazon Resource Names (ARNs)](wiki/Page-02-ARNs.md)  
3. [Security Token Service (STS)](wiki/Page-03-STS.md)  
4. [AWS Identity Hierarchy](wiki/Page-04-Identity-Hierarchy.md)  
5. [IAM Policies Deep Dive](wiki/Page-05-IAM-Policies.md)  
6. [Identity in Console, CLI, and IaC](wiki/Page-06-Identity-Access-Paths.md)

### **Organizational Governance**
7. [AWS Organizations](wiki/Page-07-AWS-Organizations.md)  
8. [Service Control Policies (SCPs)](wiki/Page-08-SCPs.md)  
9. [Permission Boundaries](wiki/Page-09-Permission-Boundaries.md)

### **Workload Identity**
10. [Workload Identity (Lambda, EC2, ECS, EKS IRSA, Step Functions)](wiki/Page-10-Workload-Identity.md)

### **Data + Network Identity**
11. [Data Service Identity Models](wiki/Page-11-Data-Identity-Models.md)  
12. [Network Identity & Governance](wiki/Page-12-Network-Identity.md)

### **Advanced Identity Patterns**
13. [Cross-Account Identity Architecture](wiki/Page-13-Cross-Account-Identity.md)  
14. [CI/CD Identity Architecture](wiki/Page-14-CICD-Identity.md)  
15. [KMS Encryption Identity](wiki/Page-15-KMS-Encryption-Identity.md)  
16. [End-to-End Identity Blueprints](wiki/Page-16-End-to-End-Blueprints.md)  
17. [Best Practices Summary](wiki/Page-17-Best-Practices.md)

### **Full Architecture Map**
18. [Complete AWS Identity Architecture Map](wiki/Page-18-Identity-Architecture-Map.md)

---

## 🧩 Repository Purpose

This repository acts as a **complete AWS identity reference**, designed for:

- Security engineers  
- Cloud architects  
- DevOps teams  
- Platform engineering teams  
- Developers needing structured AWS access patterns  
- Organizations building Zero Trust architecture in AWS  

It provides both conceptual depth and practical guidance, including patterns used at enterprise scale.

---

## 🧪 Mermaid Diagrams

GitHub natively renders Mermaid diagrams.  
Each wiki page includes diagrams such as:

- IAM policy evaluation flows  
- STS delegation paths  
- AWS Organization structures  
- Cross-account trust models  
- Workload identity flows  
- KMS dual-policy evaluation  
- Full AWS identity architecture blueprint  

No dependencies or plugins required.

---

## 📦 Master Document

You can also view the entire guide as a single long-form document:

- **[AWS-Identity-Architecture.md](AWS-Identity-Architecture.md)**

---

## 🛠 Contributing

Pull requests are welcome!  
Additions may include:

- Examples (Terraform, CloudFormation, CDK)  
- Additional diagrams  
- Real-world architecture patterns  
- Integration examples for SaaS or CI/CD tools  

For major changes, please open an issue first to discuss.

---

## 📄 License

Add a license here (MIT, Apache-2.0, etc.) depending on your publishing intent.

---

## ⭐ Acknowledgments

This knowledgebase was designed to serve as an end-to-end AWS identity guide, combining foundational principles with real-world architectural best practices.
