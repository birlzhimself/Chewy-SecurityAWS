![https://i.ibb.co/Wx7ZrTH/Screenshot-2023-05-31-222753.jpg](https://i.ibb.co/Wx7ZrTH/Screenshot-2023-05-31-222753.jpg)

# Chewy-Security AWS

## Overview

Chewy's executives want to start increasing sales to Europe as part of their expansion strategy. Regrettably, GDPR has caused a hiccup in the process. The CEO of Chewy explains, "Up until recently, when we expanded our shipping clients to the worldwide market, we've never dealt with consumer privacy regulations. "I'm hoping that our new cybersecurity consultants can put in place some systems and processes that will keep us GDPR compliant and also show customers that Chewy is a company that takes their data privacy seriously," said the new hire.

## Project Objectives:

The goal of Chewy Security AWS is to safeguard personally identifiable information (PII) and payment card industry (PCI) data while enabling Chewy's development into Europe and maintaining GDPR compliance. The project's goal is to showcase a strong cybersecurity infrastructure in the AWS Cloud, demonstrating the application of several security mechanisms to stop illegal access and data exfiltration.

**Objective 1.**

* Proper IAM for all team members must be implemented using AWS best practices
* Use root sparingly and with MFA
* Administrator permissions OK

**Objective 2. CIS-compliant Data Server**

* Chewy maintains a Linux server instance containing PII and PCI data
* PII and PCI data needs to be encrypted at rest and in transit

**Objective 3. SIEM/log aggregation system**

* Options include Splunk Enterprise (Trial), CloudWatch, and Elastic Stack
* Configure to ingest event logs in real time from key assets
* Demonstrate an attack TTP with a goal of PII/PCI data exfiltration. The attack should trigger an event that gets ingested by the SIEM and raises an alert of some kind that notifies an administrator via SMS or SMTP

**Objective 4. Cloud Monitoring**

* Capture traffic for the client to demonstrate how a data exfiltration attempt will be detected in the AWS Cloud using VPC Flow Logs and any additional automation necessary
* An AWS Lambda function triggering a relevant response to a detected threat (this fulfills the requirement for a shell script)

**Objective 5. DLP controls**

* Implement a DLP solution of your choosing on a transport protocol of your choosing
* Configured to detect and prevent the exfiltration of PII and PCI data classes from an instance or instances

**Objective 6. Novelty**

* Challenge yourselves to implement a novel tool, system, or technique that was not demonstrated or performed during lab time in term 1 of your Ops 401 class

## Network Topology:

![https://i.ibb.co/xJvvdNF/AWSTopology.jpg](https://i.ibb.co/xJvvdNF/AWSTopology.jpg)

## Deliverables:

- [Project Plan](https://docs.google.com/document/d/1PaMgX8umSwd43FG2Iz_wzYJZdSnE6O4M3tAkEPKg2sw/edit?usp=sharing)
- [Project Report](https://docs.google.com/document/d/1c9sl-zDqpSAXWJocXoAe6HKFAgPYL8mNjWGkYOewlO4/edit?usp=sharing)
- [Demo Day Slide Deck](https://drive.google.com/file/d/1xjN78UAjZ6FYvJ5Mz-xo8ofXB_W5B7-G/view?usp=sharing)
- [Team Agreements](https://github.com/birlzhimself/Chewy-SecurityAWS/blob/main/TeamAgreements/TeamAgreements.md)

## Team Contributors:

| [![Hugo Rebelo](https://avatars.githubusercontent.com/u/122793759?v=4&s=144)](https://github.com/birlzhimself) | [![Sérgio Charruadas](https://avatars.githubusercontent.com/u/20626461?v=4&s=144)](https://github.com/itzvenom) | [![Diogo Henriques](https://avatars.githubusercontent.com/u/125299195?v=4&s=144)](https://github.com/diohen90) |
|---|---|---|
| [Hugo Rebelo](https://github.com/birlzhimself) | [Sérgio Charruadas](https://github.com/itzvenom) | [Diogo Henriques](https://github.com/diohen90) |
