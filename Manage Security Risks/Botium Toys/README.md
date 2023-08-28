-------------------------
# Botium Toys Assessments
-------------------------

## Table of Contents
- [Introduction](#Introduction)
- [Audit Checklists](#AuditChecklist)
- [Control Assessment](#ControlAssessment)
- [Compliance Checklists](#ComplianceChecklists)
- [StakeHolder Memorandum](#StakeHoldersMemorandum)
   

## Introduction <a name="Introduction">
Botium Toys is a small U.S. business that develops and sells toys. The business has a single physical location. However, its online presence has grown, attracting customers in the U.S. and abroad. Their information technology (IT) department is under increasing pressure to support their online market worldwide. 

Objective: Evaluate Botium Toys' cybersecurity program, align it with industry standards, and provide solutions for high-risk vulnerabilities.
The aim is to enhance Botium Toys' cybersecurity posture by identifying weaknesses, providing actionable solutions, and ensuring alignment with industry standards.

The goals for Botium Toys’ internal IT audit are:
  - To adhere to the National Institute of Standards and Technology Cybersecurity
     Framework (NIST CSF)
  - Establish a better process for their systems to ensure they are compliant
  - Fortify system controls
  - Implement the concept of least permissions when it comes to user credential
    management
  - Establish their policies and procedures, which includes their playbooks
  - Ensure they are meeting compliance requirements

## Audit checklist <a name="AuditChecklist">

1. Identify the scope of the audit
2. Complete a risk assessment
3. Conduct the audit
4. Create a mitigation plan
5. Communicate results to stakeholders

## Controls assessment <a name="ControlAssessment">
To review control categories, types, and the purposes of each, read the control categories document.
Current assets
Assets managed by the IT Department include: 
-	On-premises equipment for in-office business needs  
-	Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.
-	Management of systems, software, and services: accounting, telecommunication, database, security, ecommerce, and inventory management
-	Internet access
- Internal network
-	Vendor access management
-	Data center hosting services  
-	Data retention and storage
-	Badge readers
-	Legacy system maintenance: end-of-life systems that require human monitoring 

### Administrative Controls
| Control Name | Control Type and Explanation | Needs to be implemented (X) | Priority |
| --- | --- | --- | --- |
| Least Privilege | Preventative; reduces risk by making sure vendors and non-authorized staff only have access to the assets/data they need to do their jobs | X | High |
| Disaster recovery plans | Corrective; business continuity to ensure systems are able to run in the event of an incident/there is limited to no loss of productivity downtime/impact to system components, including: computer room environment (air conditioning, power supply, etc.); hardware (servers, employee equipment); connectivity (internal network, wireless); applications (email, electronic data); data and restoration | X | Medium/High |
| Password policies | Preventative; establish password strength rules to improve security/reduce likelihood of account compromise through brute force or dictionary attack techniques | X | High |
| Access control policies | Preventative; reduce attack surface and limit overall impact from disgruntled/former employees | X | High |
| Account management policies | Preventative; reduce attack surface and limit overall impact from disgruntled/former employees | X | High |
| Separation of duties | Preventative; ensure no one has so much access that they can abuse the system for personal gain | X | High |

### Technical Controls 
| Control Name | Control type and explanation | Needs to be implemented (X) | Priority |
| --- | --- | --- | --- |
| Firewall | Preventative; firewalls ***are already in place*** to filter unwanted/malicious traffic from entering internal network | NA | NA |
| Intrusion Detection System (IDS) | Detective; allows IT team to identify possible intrusions (e.g., anomalous traffic) quickly | X | High |
| Encryption | Deterrent; makes confidential information/data more secure (e.g., website payment transactions) | X | High |
| Backups | Corrective; supports ongoing productivity in the case of an event; aligns to the disaster recovery plan | X | High |
| Password management system | Corrective; password recovery, reset, lock out notifications | X | High |
| Antivirus (AV) software | Corrective; detect and quarantine known threats | X | High |
| Manual monitoring, maintenance, and intervention | Preventative/corrective; required for legacy systems to identify and mitigate potential threats, risks, and vulnerabilities | X | High |

### Physical Controls
| Control Name | Control type and explanation | Needs to be implemented (X) | Priority |
| --- | --- | --- | --- |
| Time-controlled safe | Deterrent; reduce attack surface/impact of physical threats | X | Medium |
| Adequate lighting | Deterrent; limit “hiding” places to deter threats | X | Medium |
| Closed-circuit television (CCTV) surveillance | Preventative/detective; can reduce risk of certain events; can be used after event for investigation | X | Medium/High |
| Locking cabinets (for network gear) | Preventative; increase integrity by preventing unauthorized personnel/individuals from physically accessing/modifying network infrastructure gear | X | Medium/High |
| Signage indicating alarm service provider | Deterrent; makes the likelihood of a successful attack seem low | X | Low |
| Locks | Preventative; physical and digital assets are more secure | X | High |
| Fire detection and prevention (fire alarm, sprinkler system, etc.) | Detective/Preventative; detect fire in the toy store’s physical location to prevent damage to inventory, servers, etc. | X | Medium/High |

# Compliance checklists <a name="ComplianceChecklists">  
To review compliance regulations and standards, read the controls, frameworks, and compliance document.

- General Data Protection Regulation (GDPR)
   - GDPR is a European Union (E.U.) general data regulation that protects the processing of E.U. citizens’ data and their right to privacy in and out of E.U. territory. Additionally, if a breach occurs and a E.U. citizen’s data is compromised, they must be informed within 72 hours of the incident.
     - Explanation: Botium Toys is expanding its services internationally, including handling customer data from the European Union. To ensure compliance with GDPR regulations, we will prioritize the secure and lawful handling of financial and personal information of EU customers.

- Payment Card Industry Data Security Standard (PCI DSS)
   - PCI DSS is an international security standard meant to ensure that organizations storing, accepting, processing, and transmitting credit card information do so in a secure environment. 
     - Explanation: Botium Toys must follow PCI DSS rules because they accept payments and store customer credit card data. Not following these rules can lead to costly fines, audits after data breaches, payment restrictions, damage to the company's reputation, and potential lawsuits.

- System and Organizations Controls (SOC type 1, SOC type 2)
   - The SOC1 and SOC2 are a series of reports that focus on an organization’s user access policies at different organizational levels. They are used to assess an organization’s financial compliance and levels of risk. They also cover confidentiality, privacy, integrity, availability, security, and overall data safety. Control failures in these areas can lead to fraud.
     - Explanation: Botium Toys must ensure proper user access controls for both internal and external personnel, including third-party vendors. This is crucial for reducing risks and safeguarding data.
Two key standards for evaluating internal controls are SOC1 and SOC2. SOC1 primarily assesses financial reporting controls, while SOC2 focuses on information security controls, specifically the safety of customer data.

-----------------------

# StakeHolders Memorandum <a name="StakeHoldersMemorandum">

To : IT Manager & Stakeholders\
From : Ammiroul Amin\
Date : 23/8/2023

Subject : Internal IT audit findings and recommendations


Dear IT Manager and Stakeholders,

I'd like to share the key findings and recommendations from our recent internal IT audit at Botium Toys.

Scope:
- We audited the following systems:

  - Accounting
  - Endpoint detection
  - Firewalls
  - Intrusion detection system
  - Security information and event management (SIEM) tool

- We evaluated these systems for:

  - Current user permissions
  - Implemented controls
  - Procedures and protocols
  - Alignment with GDPR, PCI DSS, and compliance requirements
  - Technology and asset accountability

Goals:
- Our goals were to:

  - Follow the NIST CSF framework
  - Establish a compliant process
  - Strengthen system controls
  - Implement the principle of least privilege
  - Develop policies, including playbooks

Critical Findings (Immediate Action Required):
- We identified several critical issues that must be addressed immediately:

  - Implement the Principle of Least Privilege and Separation of Duties
  - Develop disaster recovery plans
  - Implement password, access control, and account management policies
  - Enhance the Intrusion Detection System (IDS)
  - Implement encryption for secure transactions and sensitive data storage
  - Establish robust backup procedures
  - Implement a password management system
  - Deploy antivirus (AV) software
  - Address manual monitoring for legacy systems
  - Enhance closed-circuit television (CCTV) surveillance
  - Improve physical security with locks, locking cabinets, and fire detection/prevention

- Policy Development (To Meet Compliance Requirements):\
We recommend developing and implementing policies to meet PCI DSS, GDPR, SOC1, and SOC2 compliance requirements.These policies should focus on user access and overall data safety.

- Non-Critical Findings (Address After Critical Issues):\
After addressing critical issues, consider the following physical controls:

  - Time-controlled safe
  - Adequate lighting
  - Signage indicating alarm service provider for restricted areas

Summary and Recommendations:\
   We strongly recommend addressing critical compliance issues with PCI DSS and GDPR swiftly, as Botium Toys handles online payments from global customers, including the EU. To achieve the goal of least permissions, follow SOC1 and SOC2 guidance for user access policies and data safety procedures. Having disaster recovery plans and backups is essential for business continuity in case of incidents. Integrating an IDS and AV software will enhance risk detection and intrusion prevention, especially for legacy systems needing manual monitoring. To secure physical assets at Botium Toys' location, use locks and CCTV. Consider encryption, a time-controlled safe, adequate lighting, locking cabinets, fire prevention, and alarm signage for further security, though these can be addressed gradually.

Your attention to these recommendations will significantly improve Botium Toys' security and compliance posture.

Best regards,\
Ammiroul Amin

# Conclusion
As per conclusion , I learn many new things on this assessment on how to write in Github , how to create a full report on auditing. I literally had no background in cybersecurity. I'm looking forward to learn more and many thing in CyberSecurity . Thank you 

