# AWS Identity Architecture — Wiki Home

Welcome to the AWS Identity Architecture Wiki.

This knowledgebase provides a complete, 18-page deep-dive into how identity, permissions, and authorization work across AWS. It covers IAM, STS, Organizations, SCPs, workload identity, data and network identity models, KMS, CI/CD access patterns, and full end-to-end architecture diagrams.

Use this wiki as a reference for designing secure, scalable, and production-ready AWS environments.

---

## 📚 Table of Contents

### **Core Identity Concepts**
1. **[IAM Foundations](Page-01-IAM-Foundations.md)**  
2. **[Amazon Resource Names (ARNs)](Page-02-ARNs.md)**  
3. **[Security Token Service (STS)](Page-03-STS.md)**  
4. **[AWS Identity Hierarchy](Page-04-Identity-Hierarchy.md)**  
5. **[IAM Policies Deep Dive](Page-05-IAM-Policies.md)**  
6. **[Identity in Console, CLI, and IaC](Page-06-Identity-Access-Paths.md)**  

---

### **Organizational Governance**
7. **[AWS Organizations](Page-07-AWS-Organizations.md)**  
8. **[Service Control Policies (SCPs)](Page-08-SCPs.md)**  
9. **[Permission Boundaries](Page-09-Permission-Boundaries.md)**  

---

### **Workload Identity**
10. **[Workload Identity (Lambda, EC2, ECS, EKS IRSA, Step Functions)](Page-10-Workload-Identity.md)**  

---

### **Data & Network Identity**
11. **[Data Service Identity Models](Page-11-Data-Identity-Models.md)**  
12. **[Network Identity & Governance](Page-12-Network-Identity.md)**  

---

### **Advanced Identity Patterns**
13. **[Cross-Account Identity Architecture](Page-13-Cross-Account-Identity.md)**  
14. **[CI/CD Identity Architecture](Page-14-CICD-Identity.md)**  
15. **[KMS Encryption Identity](Page-15-KMS-Encryption-Identity.md)**  
16. **[End-to-End Identity Blueprints](Page-16-End-to-End-Blueprints.md)**  
17. **[Best Practices Summary](Page-17-Best-Practices.md)**  

---

### **Full Architecture Map**
18. **[Complete AWS Identity Architecture Map](Page-18-Identity-Architecture-Map.md)**  

---

## 🧩 What This Wiki Is
This wiki is a comprehensive reference intended for:

- Cloud security engineers  
- Platform engineering teams  
- DevOps and SRE teams  
- Architects building secure multi-account AWS environments  
- Developers who need clarity on AWS identity and permissions  

It explains not just *how* AWS identity works, but *why*, and how to apply these models to real-world architectures.

---

## 🧪 Diagram Support

All pages include Mermaid diagrams illustrating:

- IAM evaluation flow  
- STS delegation  
- AWS Organization structures  
- CI/CD role assumption  
- Workload identity flows  
- KMS dual-policy authorization  
- The full AWS Identity Architecture map  

GitHub automatically renders these diagrams in your wiki.

---

## 📦 Master Document

For a single long-form view, see the main repository file:

- **AWS-Identity-Architecture.md**

---

## 💬 Contributing

Contributions are welcome—open issues, add examples, propose clarifications, or include additional identity patterns such as:

- Terraform or CloudFormation examples  
- OIDC trust policies for GitHub/GitLab  
- Account vending patterns  
- Zero-Trust network identity  

---

## ⭐ Thanks for Visiting

This knowledgebase is meant to be both educational and operational.  
Use it to design secure, scalable identity systems in AWS.

