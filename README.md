# Hands-on-AWS-Cloud-Security-EKS-WAF-Incident-Response-CTF-Labs-SecByte-Index
A practical collection of cybersecurity CTF labs covering Amazon Web Services (AWS) security, EKS Kubernetes clusters, GuardDuty threat detection, CloudTrail forensics, AWS WAF, Lambda IAM abuse, and AWS Security Hub incident response.
# AWS Cloud Security, EKS, WAF & Incident Response CTF Lab Collection

Welcome to the **AWS Cloud Security, EKS, WAF & Incident Response CTF Lab Collection**. This repository serves as a practical, searchable index of hands-on security labs and Capture The Flag (CTF) challenges hosted on Learn SecByte.

This catalog covers core Amazon Web Services (AWS) security engineering and SecOps disciplines, including Amazon EKS cluster security, GuardDuty threat detection, CloudTrail intrusion tracing, Lambda IAM abuse, AWS WAF/Shield edge defense, and AWS Security Hub incident response.

---

## Lab Collection Index

### 1. AWS Cloud Threat Detection, Forensics & Telemetry
* **AWS GuardDuty: Cloud Threat Detection and Investigation**  
  *Lab Link:* [https://learn.secbyte.org/ctf/aws-guardduty-cloud-threat-detection-and-investigation](https://learn.secbyte.org/ctf/aws-guardduty-cloud-threat-detection-and-investigation)  
  *Focus:* Triaging automated GuardDuty findings, detecting compromised EC2 instances, unauthorized IAM credential usage, and DNS exfiltration.

* **AWS CloudTrail Investigation: Find the Trail, Trace the Intrusion**  
  *Lab Link:* [https://learn.secbyte.org/ctf/aws-cloudtrail-investigation-find-the-trail-trace-the-intrus](https://learn.secbyte.org/ctf/aws-cloudtrail-investigation-find-the-trail-trace-the-intrus)  
  *Focus:* Querying management and data event logs, tracing unauthorized API calls, identifying user agents, and reconstructing attacker timelines.

* **AWS Detective: Cloud Investigation and Evidence Correlation**  
  *Lab Link:* [https://learn.secbyte.org/ctf/aws-detective-cloud-investigation-and-evidence-correlation](https://learn.secbyte.org/ctf/aws-detective-cloud-investigation-and-evidence-correlation)  
  *Focus:* Using visual graph analytics to correlate CloudTrail, VPC Flow Logs, and GuardDuty data to investigate root causes of intrusions.

* **AWS CloudWatch Monitoring: Detecting Misconfigurations and Suspicious Activity**  
  *Lab Link:* [https://learn.secbyte.org/ctf/aws-cloudwatch-monitoring-detecting-misconfigurations-and-su](https://learn.secbyte.org/ctf/aws-cloudwatch-monitoring-detecting-misconfigurations-and-su)  
  *Focus:* Creating metric filters, setting up alarm triggers, configuring log groups, and detecting real-time configuration changes.

### 2. AWS Edge Defense, Governance & Compliance
* **AWS WAF: Defending and Testing Web Apps at the Edge**  
  *Lab Link:* [https://learn.secbyte.org/ctf/aws-waf-defending-and-testing-web-apps-at-the-edge](https://learn.secbyte.org/ctf/aws-waf-defending-and-testing-web-apps-at-the-edge)  
  *Focus:* Deploying WebACLs, configuring rate-based rules, applying OWASP core rule sets, and testing application defenses against web attacks.

* **AWS Shield: Understanding and Defending Against DoS**  
  *Lab Link:* [https://learn.secbyte.org/ctf/aws-shield-understanding-and-defending-against-dos](https://learn.secbyte.org/ctf/aws-shield-understanding-and-defending-against-dos)  
  *Focus:* Mitigating volumetric Layer 3/4 and application Layer 7 DDoS attacks, configuring Shield Advanced health checks, and route protection.

* **AWS Security Hub: Cloud Security Findings, Triage, and Response**  
  *Lab Link:* [https://learn.secbyte.org/ctf/aws-security-hub-cloud-security-findings-triage-and-response](https://learn.secbyte.org/ctf/aws-security-hub-cloud-security-findings-triage-and-response)  
  *Focus:* Centralizing security findings, auditing against CIS AWS Foundations Benchmarks, and configuring automated response custom actions.

* **AWS Inspector: Cloud Vulnerability Discovery and Risk Prioritization**  
  *Lab Link:* [https://learn.secbyte.org/ctf/aws-inspector-cloud-vulnerability-discovery-and-risk-priorit](https://learn.secbyte.org/ctf/aws-inspector-cloud-vulnerability-discovery-and-risk-priorit)  
  *Focus:* Automating vulnerability scans for EC2 instances and ECR container images, evaluating CVE severity scores, and patch management.

* **AWS Config: Cloud Change Detection and Governance**  
  *Lab Link:* [https://learn.secbyte.org/ctf/aws-config-cloud-change-detection-and-governance](https://learn.secbyte.org/ctf/aws-config-cloud-change-detection-and-governance)  
  *Focus:* Tracking resource configuration history, defining custom compliance rules, detecting configuration drift, and trigger remediation.

* **AWS Organizations: Security Guardrails and Blast Radius Control**  
  *Lab Link:* [https://learn.secbyte.org/ctf/aws-organizations-security-guardrails-and-blast-radius-contr](https://learn.secbyte.org/ctf/aws-organizations-security-guardrails-and-blast-radius-contr)  
  *Focus:* Enforcing Service Control Policies (SCPs), multi-account isolation strategies, organizational unit (OU) design, and centralized logging.

### 3. AWS Container & Serverless Security
* **AWS EKS Security: From Cluster Basics to Detection and Defense**  
  *Lab Link:* [https://learn.secbyte.org/ctf/aws-eks-security-from-cluster-basics-to-detection-and-defens](https://learn.secbyte.org/ctf/aws-eks-security-from-cluster-basics-to-detection-and-defens)  
  *Focus:* Securing Elastic Kubernetes Service (EKS) control plane logs, IRSA (IAM Roles for Service Accounts), VPC CNI networking, and runtime auditing.

* **AWS Lambda Security: Serverless Misconfigurations, IAM Abuse, and Defense**  
  *Lab Link:* [https://learn.secbyte.org/ctf/aws-lambda-security-serverless-misconfigurations-iam-abuse-a](https://learn.secbyte.org/ctf/aws-lambda-security-serverless-misconfigurations-iam-abuse-a)  
  *Focus:* Identifying over-privileged Lambda execution roles, event source mapping abuse, environment variable exploitation, and function isolation.

---

## Learning Path

### Path A: AWS SOC Analyst & Cloud Incident Responder
1. **Telemetry & Detection:** Start with [AWS GuardDuty](https://learn.secbyte.org/ctf/aws-guardduty-cloud-threat-detection-and-investigation) and [AWS CloudWatch Monitoring](https://learn.secbyte.org/ctf/aws-cloudwatch-monitoring-detecting-misconfigurations-and-su).
2. **Forensic Analysis:** Execute investigations via [AWS CloudTrail Investigation](https://learn.secbyte.org/ctf/aws-cloudtrail-investigation-find-the-trail-trace-the-intrus) and [AWS Detective](https://learn.secbyte.org/ctf/aws-detective-cloud-investigation-and-evidence-correlation).
3. **Centralized Incident Management:** Triage findings in [AWS Security Hub](https://learn.secbyte.org/ctf/aws-security-hub-cloud-security-findings-triage-and-response).

### Path B: AWS Cloud Security Engineer & Governance Lead
1. **Governance & Guardrails:** Begin with [AWS Organizations](https://learn.secbyte.org/ctf/aws-organizations-security-guardrails-and-blast-radius-contr) and [AWS Config](https://learn.secbyte.org/ctf/aws-config-cloud-change-detection-and-governance).
2. **Vulnerability & Edge Defense:** Implement controls with [AWS Inspector](https://learn.secbyte.org/ctf/aws-inspector-cloud-vulnerability-discovery-and-risk-priorit), [AWS WAF](https://learn.secbyte.org/ctf/aws-waf-defending-and-testing-web-apps-at-the-edge), and [AWS Shield](https://learn.secbyte.org/ctf/aws-shield-understanding-and-defending-against-dos).
3. **Container & Serverless Security:** Hardened workloads using [AWS EKS Security](https://learn.secbyte.org/ctf/aws-eks-security-from-cluster-basics-to-detection-and-defens) and [AWS Lambda Security](https://learn.secbyte.org/ctf/aws-lambda-security-serverless-misconfigurations-iam-abuse-a).

---

## How to Use the Labs

1. Select a practice scenario from the **Lab Collection Index**.
2. Click the direct link to launch the lab environment hosted on Learn SecByte.
3. Review scenario objectives, infrastructure architecture, and task constraints.
4. Complete security checks, analyze AWS logs, or remediate cloud misconfigurations to capture flags.

---

## Target Audience

* **Cloud Security Engineers:** Implement robust security guardrails, edge WAF defenses, and EKS cluster controls.
* **SOC Analysts & Incident Responders:** Investigate CloudTrail events, correlate signals with AWS Detective, and triage GuardDuty alerts.
* **DevSecOps Engineers:** Automate vulnerability management with AWS Inspector and enforce configuration compliance via AWS Config.
* **Cybersecurity Students:** Acquire hands-on experience in cloud threat detection and AWS security operations.

---

## Disclaimer

All lab links in this repository direct to official training environments hosted on Learn SecByte. These materials are provided exclusively for authorized security training, defensive skill building, and educational research. Unapproved testing against external AWS infrastructure is strictly prohibited.
