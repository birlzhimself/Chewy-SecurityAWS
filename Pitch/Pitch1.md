## Project Name: Chewy Security AWS

### Summary of Idea:
Chewy Security AWS is a comprehensive security solution designed to enable Chewy's expansion into Europe while ensuring compliance with GDPR regulations and protecting personally identifiable information (PII) and payment card industry (PCI) data. The project aims to demonstrate a robust cybersecurity infrastructure in AWS Cloud, showcasing the implementation of various security measures to prevent unauthorized access and data exfiltration.

### Problem/Pain Point:
Chewy's expansion into the European market has brought the challenge of complying with GDPR regulations and safeguarding customer data. Chewy Security AWS addresses this pain point by providing a solution that ensures data privacy, builds trust with customers, and establishes Chewy as a brand committed to protecting sensitive data.

### Minimum Viable Product (MVP) Definition:
The MVP for the demo day presentation of Chewy Security AWS would include the implementation and demonstration of the following components:

 IAM Best Practices: Implement proper AWS Identity and Access Management (IAM) using best practices, including limited use of root access, multi-factor authentication (MFA), and appropriate permissions for team members.

CIS-Compliant Data Server: Deploy a secure Linux server instance on AWS, encrypting PII and PCI data both at rest and in transit according to CIS standards.

SIEM/Log Aggregation: Configure a Security Information and Event Management (SIEM) system, such as Splunk Enterprise, CloudWatch, or Elastic Stack, to ingest real-time event logs from critical assets. Simulate an attack on PII/PCI data, triggering SIEM alerts for immediate response.

Cloud Monitoring: Utilize VPC Flow Logs and other relevant tools to capture and analyze network traffic in AWS, showcasing how data exfiltration attempts are detected. Implement AWS Lambda functions to automate responses to identified threats.

DLP Controls: Implement a Data Loss Prevention (DLP) solution on a chosen transport protocol to detect and prevent the unauthorized exfiltration of PII and PCI data. Showcase the effectiveness of the DLP controls in preventing data breaches.

Innovation: Demonstrate the implementation of a novel tool, system, or technique that goes beyond the standard practices covered in the course. Showcase an innovative approach to enhance data protection, threat detection, or incident response capabilities.

By presenting the above MVP components, Chewy Security AWS showcases a robust security infrastructure that ensures GDPR compliance, protects PII and PCI data, and establishes Chewy as a trusted brand committed to data privacy and customer trust.
