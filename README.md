# 50 Cloud Security & Penetration Testing Projects

A practical, multi-cloud learning portfolio covering **Amazon Web Services (AWS), Microsoft Azure, and Google Cloud Platform (GCP)**. The collection is organized into 15 beginner, 20 intermediate, and 15 advanced projects.

> **Authorization:** Use dedicated lab accounts and explicitly authorized environments only. Most exercises prioritize read-only security assessment and defensive validation. Advanced attack-path topics are framed as controlled simulations and configuration reviews, not instructions for unauthorized access. Screenshots marked simulated contain fictional output and are not real assessment evidence.

## Learning path

| Level | Projects | Focus |
|---|---:|---|
| Beginner | 01–15 | Cloud foundations, inventory, IAM, storage, exposure, logging, encryption, posture |
| Intermediate | 16–35 | Identity permissions, compute, metadata, serverless, APIs, Kubernetes, secrets, databases, segmentation, federation |
| Advanced | 36–50 | Attack-path analysis, trust boundaries, safe lateral-movement simulations, CI/CD, IaC, detection, incident response, full assessment |

## Beginner projects

01. [Cloud Environment Setup and Security Lab — AWS / Azure / GCP](beginner/01-cloud-environment-setup/README.md)
02. [Cloud Asset Discovery and Inventory — AWS / Azure / GCP](beginner/02-cloud-asset-discovery/README.md)
03. [AWS IAM User and Role Security Assessment — AWS](beginner/03-aws-iam-security-assessment/README.md)
04. [Azure Entra ID Identity Security Assessment — Azure](beginner/04-azure-entra-id-security-assessment/README.md)
05. [GCP IAM Roles and Permissions Assessment — GCP](beginner/05-gcp-iam-security-assessment/README.md)
06. [Cloud Storage Security Assessment — AWS / Azure / GCP](beginner/06-cloud-storage-security-assessment/README.md)
07. [Public Cloud Resource Exposure Assessment — AWS / Azure / GCP](beginner/07-public-resource-exposure-assessment/README.md)
08. [Cloud Security Group and Firewall Assessment — AWS / Azure / GCP](beginner/08-cloud-firewall-security-assessment/README.md)
09. [Cloud Network Architecture Review — AWS / Azure / GCP](beginner/09-cloud-network-architecture-review/README.md)
10. [Cloud Logging and Audit Configuration Assessment — AWS / Azure / GCP](beginner/10-cloud-logging-audit-assessment/README.md)
11. AWS S3 Bucket Permissions Testing — AWS
12. Azure Blob Storage Permissions Testing — Azure
13. GCP Cloud Storage Permissions Testing — GCP
14. Cloud Encryption and Key Management Review — AWS / Azure / GCP
15. Cloud Security Posture Assessment — AWS / Azure / GCP

## Intermediate projects

16. AWS IAM Privilege Escalation Assessment — AWS
17. Azure RBAC Privilege Escalation Assessment — Azure
18. GCP IAM Privilege Escalation Assessment — GCP
19. AWS EC2 Instance Security Testing — AWS
20. Azure Virtual Machine Security Testing — Azure
21. GCP Compute Engine Security Testing — GCP
22. Cloud Metadata Service Security Testing — AWS / Azure / GCP
23. Serverless Function Security Assessment — AWS / Azure / GCP
24. AWS Lambda Security Testing — AWS
25. Azure Functions Security Testing — Azure
26. GCP Cloud Functions Security Testing — GCP
27. Cloud API Security Assessment — AWS / Azure / GCP
28. Cloud Kubernetes Security Assessment — AWS / Azure / GCP
29. AWS EKS Security Testing — AWS
30. Azure AKS Security Testing — Azure
31. GCP GKE Security Testing — GCP
32. Cloud Secrets Management Assessment — AWS / Azure / GCP
33. Cloud Database Security Assessment — AWS / Azure / GCP
34. Cloud Network Segmentation Testing — AWS / Azure / GCP
35. Cloud Identity Federation Security Testing — AWS / Azure / GCP

## Advanced projects

36. AWS Cloud Attack Path Analysis — AWS
37. Azure Cloud Attack Path Analysis — Azure
38. GCP Cloud Attack Path Analysis — GCP
39. Cross-Account Access and Trust Abuse Assessment — AWS
40. Azure Managed Identity Security Assessment — Azure
41. GCP Service Account Impersonation Assessment — GCP
42. Cloud Lateral Movement Simulation — AWS / Azure / GCP
43. Cloud Persistence and Privilege Abuse Assessment — AWS / Azure / GCP
44. Cloud Container Escape and Isolation Assessment — AWS / Azure / GCP
45. Cloud CI/CD Pipeline Security Assessment — AWS / Azure / GCP
46. Infrastructure as Code Security Assessment — AWS / Azure / GCP
47. Cloud Data Exfiltration Risk Simulation — AWS / Azure / GCP
48. Cloud Threat Detection and Incident Response Testing — AWS / Azure / GCP
49. Multi-Cloud Security Architecture and Threat Modeling — AWS / Azure / GCP
50. Complete Multi-Cloud Penetration Test — AWS / Azure / GCP

## Repository structure

```text
beginner/       # 15 guided projects
intermediate/   # 20 guided projects
advanced/       # 15 guided projects
_assets/screenshots/  # Simulated tool screenshots used in walkthroughs
REPORT_TEMPLATE.md
CONTRIBUTING.md
```

Each completed project README includes its objective, prerequisites, tools, step-by-step walkthrough, embedded simulated screenshots, expected observations, remediation, evidence handling, and reporting guidance. Projects are published in batches; an item without a link is planned, not yet documented.
