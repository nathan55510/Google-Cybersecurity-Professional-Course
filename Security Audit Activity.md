# Scenario

Review the following scenario. Then complete the step-by-step instructions.

This scenario is based on a fictional company:

Botium Toys is a small U.S. business that develops and sells toys. The business has a single physical location, which serves as their main office, a storefront, and warehouse for their products. However, Botium Toy’s online presence has grown, attracting customers in the U.S. and abroad. As a result, their information technology (IT) department is under increasing pressure to support their online market worldwide. 

The manager of the IT department has decided that an internal IT audit needs to be conducted. She expresses concerns about not having a solidified plan of action to ensure business continuity and compliance, as the business grows. She believes an internal audit can help better secure the company’s infrastructure and help them identify and mitigate potential risks, threats, or vulnerabilities to critical assets. The manager is also interested in ensuring that they comply with regulations related to internally processing and accepting online payments and conducting business in the European Union (E.U.).   

The IT manager starts by implementing the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF), establishing an audit scope and goals, listing assets currently managed by the IT department, and completing a risk assessment. The goal of the audit is to provide an overview of the risks and/or fines that the company might experience due to the current state of their security posture.

Your task is to review the IT manager’s scope, goals, and risk assessment report. Then, perform an internal audit by completing a controls and compliance checklist. 

# Current Assets

Assets managed by the IT Department include:

● On-premises equipment for in-office business needs

● Employee equipment: end-user devices (desktops/laptops, smartphones)
remote workstations, headsets, cables, keyboards, mice, docking stations
surveillance cameras, etc.

● Storefront products available for retail sale on-site and online; stored in the
company’s adjoining warehouse

● Management of systems, software, and services: accounting
telecommunication, database, security, e-commerce, and inventory
management

● Internet access

● Internal network

● Data retention and storage

● Legacy system maintenance: end-of-life systems that require human
monitoring

# Risk assessment

Currently, there is inadequate management of assets. Additionally, Botium Toys does
not have all of the proper controls in place and may not be fully compliant with U.S. and
international regulations and standards.

Control best practices

The first of the five functions of the NIST CSF is Identify. Botium Toys will need to
dedicate resources to identify assets so they can appropriately manage them.
Additionally, they will need to classify existing assets and determine the impact of the
loss of existing assets, including systems, on business continuity.

Risk score

On a scale of 1 to 10, the risk score is 8, which is fairly high. This is due to a lack of
controls and adherence to compliance best practices.

Additional comments

The potential impact from the loss of an asset is rated as medium because the IT
department does not know which assets would be at risk. The risk to assets or fines
from governing bodies is high because Botium Toys does not have all of the necessary
controls in place and is not fully adhering to best practices related to compliance
regulations that keep critical data private/secure. Review the following bullet points for
specific details:

● Currently, all Botium Toys employees have access to internally stored data and
may be able to access cardholder data and customers’ PII/SPII.

● Encryption is not currently used to ensure confidentiality of customers’ credit
card information that is accepted, processed, transmitted, and stored locally in
the company’s internal database.

● Access controls pertaining to least privilege and separation of duties have not
been implemented.

● The IT department has ensured availability and integrated controls to ensure
data integrity.

● The IT department has a firewall that blocks traffic based on an appropriately
defined set of security rules.

● Antivirus software is installed and monitored regularly by the IT department.

● The IT department has not installed an intrusion detection system (IDS).

● There are no disaster recovery plans currently in place, and the company does
not have backups of critical data.

● The IT department has established a plan to notify E.U. customers within 72
hours if there is a security breach. Additionally, privacy policies, procedures, and
processes have been developed and are enforced among IT department
members/other employees, to properly document and maintain data.

● Although a password policy exists, its requirements are nominal and not in line
with current minimum password complexity requirements (e.g., at least eight
characters, a combination of letters and at least one number; special
characters).

● There is no centralized password management system that enforces the
password policy’s minimum requirements, which sometimes affects
productivity when employees/vendors submit a ticket to the IT department to
recover or reset a password.

● While legacy systems are monitored and maintained, there is no regular
schedule in place for these tasks and intervention methods are unclear.

● The store’s physical location, which includes Botium Toys’ main offices, store
front, and warehouse of products, has sufficient locks, up-to-date
closed-circuit television (CCTV) surveillance, as well as functioning fire
detection and prevention systems.



# My Assessment 

After reviewing Botium Toys' security posture, there are several priority areas needing improvement to address gaps in controls and compliance best practices. Implementing changes in these areas will significantly reduce Botium Toys' risk exposure.

Key findings include:

- Access management controls like least privilege and separation of duties need to be implemented to reduce insider threat risk and limit data exposure.

- Encryption should be deployed to protect confidential customer and cardholder data both at rest and in transit.
Logging, monitoring, and detection controls are lacking, including IDS/IPS, leaving malicious activity unidentified.

- Disaster recovery capabilities such as comprehensive backups and incident response plans need to be established to enable restoration after incidents.

- Network permeability should be analyzed and reduced through tighter firewall rules, network segmentation, and remote access controls.

- Password policies and password management capabilities need to be enhanced to bring complexities and management in line with best practices.

- Business continuity risks from legacy systems should be assessed and a modernization roadmap defined.

- Physical and operational security controls provide a good baseline but regular auditing will identify enhancement opportunities.

- By taking action in these key areas identified, Botium Toys can significantly improve its security posture and comply with industry best practices. The findings provide a roadmap for the security and compliance enhancements needed most.

# European Compliance

Additionally, the manager is interested in ensuring that they comply with regulations related to internally processing and accepting online payments and conducting business in the European Union (E.U.). I have assessed that compliance with data privacy regulations like GDPR needs to be reviewed and controls put in place to avoid violations and penalties:

- Audit of cardholder data environments against PCI DSS requirements and remediate any gaps.

- Assessment of customer authentication methods and protocols for PSD2 compliance.

- Review of data governance, retention and processing activities for GDPR alignment.

- Inclusion of GDPR and PCI DSS in disaster recovery and business continuity planning.

- Discussion of EU requirements and global compliance when making enhancements like logging, encryption, access controls.
