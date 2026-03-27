---
title: "<DOC_TITLE>"
weight: <DOC_WEIGHT>
---

# <ORG_NAME> <ISMS_NAME> Incident Management Procedure Policy

**Document Name:** <POLICY_CODE>-Incident_Management_Procedure  

**Classification:** <DOCUMENT_CLASSIFICATION> 

**Version:** <VERSION_NUMBER>  

**Last Review Date:** <LAST_REVIEW_DATE>  

**Approved By:** <APPROVING_BODY>  

**Approval Date:** <APPROVAL_DATE>  

**Review Period:** <REVIEW_PERIOD>  

**Status:** <DOCUMENT_STATUS>  


## 1. Document Overview

This document defines the procedure for managing information security incidents within the scope of the <ISMS_NAME>.

An **Incident** is any event that results in, or could potentially result in (including near misses), a compromise of the confidentiality, integrity, or availability of any in-scope environment, system, or data.



## 2. Incident Management Process

### 2.1 Organisational Incident Management Process

All incidents, including severe incidents affecting critical or trusted environments, shall be managed using the organisation’s standard incident management process as defined in:

- <INCIDENT_MANAGEMENT_PROCESS_REFERENCE>  

Key stages may include:

- Incident identification and reporting  
- Initial triage and classification  
- Containment and mitigation  
- Investigation and remediation  
- Closure and post-incident review  



### 2.2 Severe Incident Identification

The **Severe Incident** process shall be triggered if one or more of the following conditions are met:

- A confidentiality breach is suspected  
- An integrity breach is suspected  
- A key environment or service is completely unavailable  
- An environment is performing significantly below expected levels  
- The environment is unavailable to a significant proportion of users (e.g. <USER_IMPACT_THRESHOLD>% or more)  



## 3. Severe Incident Management

### 3.1 Roles and Responsibilities

When a Severe Incident occurs:

- Immediate actions to prevent further loss or contain damage shall not be delayed waiting for specific individuals.
- Once available, a member of the environment management team shall assume the role of **Severe Incident Manager**.

The Severe Incident Manager role may be fulfilled by:

- <ENVIRONMENT_OWNER_ROLE>  
- <ENVIRONMENT_ADMIN_ROLE>  
- <ENVIRONMENT_DEVELOPER_ROLE>  
- <INCIDENT_RESPONSE_LEAD_ROLE>

The Severe Incident Manager shall:

- Take control of incident coordination  
- Prioritise mitigation and remediation actions  
- Coordinate communication with stakeholders  
- Determine escalation and reporting requirements  

They will decide whether the incident must be classified as:

- A Critical Incident  
- An Information Security Incident  
- A Personal Data Breach  
- A Regulatory or Legal Incident  



### 3.2 Severe Incident Communication Protocol

In the event of a Severe Incident, the Severe Incident Manager shall ensure communication with the following stakeholders:

| Stakeholder / Role | Purpose |
|-------------------|---------|
| <INFORMATION_SECURITY_TEAM> | To manage and assess suspected or confirmed security breaches |
| <AFFECTED_USER_GROUP> | To provide service status, recovery updates and guidance |
| <INFORMATION_ASSET_OWNERS> | In cases of confidentiality or integrity impact |
| <DATA_CONTROLLERS_OR_DATA_PROVIDERS> | Where contractual or legal reporting obligations apply |
| <EXECUTIVE_OR_GOVERNANCE_BODY> | For significant, severe, or high-impact incidents |

Communication methods and frequency shall be defined in the <INCIDENT_COMMUNICATION_PLAN_NAME>.



## 4. Incident Reporting and Management

All incidents shall be logged using the organisation’s approved incident recording system:

- <INCIDENT_LOG_SYSTEM>

Each incident record shall include, as a minimum:

- Timeline of the incident  
- Incident classification and severity  
- Incident summary  
- Impact assessment  
- Response actions taken  
- Any changes made to systems or environments  
- Root cause analysis  
- Lessons learned and improvement actions  

Incident records shall be made available to the <ISMS_GOVERNANCE_GROUP> for review and continual improvement activities.



## 4.1 Reporting Information Security Incidents

All suspected or confirmed Information Security Incidents shall be reported to:

- <INFORMATION_SECURITY_REPORTING_CHANNEL>  
- <INFORMATION_SECURITY_TEAM>  



## 4.2 Reporting Personal Data Breaches

Personal Data Breaches shall be reported through:

- <DATA_PROTECTION_OFFICE>  
- <DATA_BREACH_REPORTING_CHANNEL>  

This must occur without undue delay and in line with applicable legal and regulatory requirements, including <REGULATORY_FRAMEWORK>.



## 5. Integration with Service Management Processes

Where internal or external service providers operate environments or services, incidents shall also follow relevant service management processes, including:

- <CRITICAL_INCIDENT_MANAGEMENT_PROCESS_REFERENCE>  
- <INCIDENT_MANAGEMENT_PROCESS_REFERENCE>  
- <PROBLEM_MANAGEMENT_PROCESS_REFERENCE>  

Integration points, responsibilities and escalation paths shall be clearly defined between service management and ISMS processes.



## Placeholder Reference 

| Placeholder | Description |
|------------|------------|
| <ORG_NAME> | Name of the organisation |
| <ISMS_NAME> | Name of the ISMS |
| <POLICY_CODE> | Internal document reference ID |
| <INCIDENT_MANAGEMENT_PROCEDURE_TITLE> | Title of this procedure |
| <VERSION_NUMBER> | Document version |
| <LAST_REVIEW_DATE> | Date of last review |
| <APPROVAL_DATE> | Date of approval |
| <APPROVING_BODY> | Governance body approving the document |
| <REVIEW_PERIOD> | Review frequency (e.g. 3 years) |
| <DOCUMENT_STATUS> | Status (Draft / Approved / Archived) |
| <DOC_WEIGHT> | Internal document ordering weight |
| <DOCUMENT_CLASSIFICATION> | Sensitivity of document |
| <INCIDENT_MANAGEMENT_PROCESS_REFERENCE> | Reference to the organisation’s incident management process |
| <ENVIRONMENT_OWNER_ROLE> | Role owning the environment |
| <ENVIRONMENT_ADMIN_ROLE> | Environment technical administrator |
| <ENVIRONMENT_DEVELOPER_ROLE> | Development role for environment |
| <INCIDENT_RESPONSE_LEAD_ROLE> | Formal incident response lead role |
| <USER_IMPACT_THRESHOLD> | Percentage of users impacted to trigger a severe incident |
| <INFORMATION_SECURITY_TEAM> | Security operations / InfoSec team |
| <INFORMATION_ASSET_OWNERS> | Asset ownership roles |
| <DATA_CONTROLLERS_OR_DATA_PROVIDERS> | Data controllers or data providers |
| <EXECUTIVE_OR_GOVERNANCE_BODY> | ISMS or organisational governance group |
| <INCIDENT_LOG_SYSTEM> | Incident management / ticketing system |
| <ISMS_GOVERNANCE_GROUP> | ISMS governance committee or board |
| <INFORMATION_SECURITY_REPORTING_CHANNEL> | Reporting mechanism for security incidents |
| <DATA_PROTECTION_OFFICE> | Data protection / privacy function |
| <DATA_BREACH_REPORTING_CHANNEL> | Mechanism for reporting data breaches |
| <REGULATORY_FRAMEWORK> | Applicable regulation (e.g. GDPR, UK DPA, HIPAA) |
| <CRITICAL_INCIDENT_MANAGEMENT_PROCESS_REFERENCE> | Reference to critical incident process |
| <PROBLEM_MANAGEMENT_PROCESS_REFERENCE> | Reference to problem management process |
| <INCIDENT_COMMUNICATION_PLAN_NAME> | Name of incident communications framework |

