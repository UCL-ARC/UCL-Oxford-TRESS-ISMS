---
title: "<DOC_TITLE>"
weight: <DOC_WEIGHT>
---

# <ORG_NAME> – <ISMS_NAME> Logging and Monitoring Policy

**Document Name:** <DOCUMENT_ID>

**Classification:** <DOCUMENT_CLASSIFICATION>

**Version:** <VERSION_NUMBER>

**Created:** <CREATION_DATE>

**Last Review Date:** <LAST_REVIEW_DATE>

**Last Reviewed by:** <REVIEWER_ROLE_OR_TITLE>

**Approved by:** <APPROVAL_BODY>

**Approval Date:** <APPROVAL_DATE>

**Review Period:** <REVIEW_PERIOD>



## 1. Document Overview

This policy defines the minimum requirements for logging and monitoring activities within <ORG_NAME>.  
It ensures that security-relevant events are recorded and that systems are actively monitored for suspicious or anomalous behaviour in alignment with ISO 27001 and relevant regulatory requirements.



## 2. Scope

This policy applies to all systems, networks, applications, and environments that fall within the scope of the <ISMS_NAME>.

Reference document: **<ISMS_SCOPE_DOCUMENT>**



## 3. Conventions Used in This Document

| Term   | Meaning                                   |
|--------|-------------------------------------------|
| Shall  | A mandatory requirement of this policy     |
| Should | A recommended requirement of this policy   |
| May    | An optional requirement of this policy     |



## 4. Logging

### 4.1 Event Logging

All critical systems, applications, and network devices shall generate security-relevant logs.

Logs shall capture events, including, but not limited to:
- User access and authentication activity  
- Privileged and administrative actions  
- System configuration changes  
- Security control events  
- Network and application-level security events  



### 4.2 Log Content Requirements

Logs should include, where technically feasible:

- Timestamp (synchronised using <TIME_SYNCHRONISATION_STANDARD>)  
- Source and destination network address  
- User or service account ID  
- Event type and classification  
- Event description and outcome (success/failure)  


### 4.3 Log Storage and Retention

1. Logs shall be stored securely and protected from unauthorised access, alteration, or deletion.  
2. Access to logs shall be restricted to authorised roles, including:
   - <SECURITY_MONITORING_ROLE>  
   - <SYSTEM_ADMIN_ROLE>
3. Where feasible, logs shall be stored outside the system or environment that generated them.  
4. Log retention shall comply with the <DATA_RETENTION_POLICY> and applicable legal or regulatory obligations.  
5. Archived logs shall be protected with equivalent security controls to live operational data.



## 5. Monitoring

Automated monitoring tools shall be deployed to identify potential security events and anomalies.

Where feasible, a <SIEM_PLATFORM> or equivalent security monitoring platform shall be implemented to:

- Correlate log data across systems  
- Detect anomalous behaviour patterns  
- Generate alerts for high-risk security events  
- Support forensic investigation and reporting  

Examples of monitored events include:
- Unauthorised access attempts  
- Privilege escalation  
- Malware detection  
- Suspicious network traffic  
- Critical service availability issues  



## 6. Incident Handling Integration

Security events and anomalies identified through monitoring shall be handled in accordance with the <INCIDENT_MANAGEMENT_PROCEDURE>.

All detected incidents shall be:
- Registered in the <INCIDENT_TRACKING_SYSTEM>  
- Investigated by the <SECURITY_OPERATIONS_FUNCTION>  
- Escalated according to severity and impact  



## 7. Review and Continuous Improvement

Logging and monitoring controls shall be reviewed regularly to ensure they remain:

- Effective  
- Proportionate  
- Aligned with evolving risks and threat landscapes  

This may include:
- Periodic log review exercises  
- Monitoring rule tuning and optimisation  
- Risk-based enhancement of alerting thresholds  


## Placeholder Reference 

| Placeholder | Description | 
|------------|------------|
| <ORG_NAME> | Name of your organisation | 
| <LOGGING_MONITORING_POLICY_NAME> | Title of this policy | 
| <LOGGING_MONITORING_POLICY_CODE> | Internal document ID | 
| <DOCUMENT_CLASSIFICATION> | Sensitivity of document | 
| <VERSION_NUMBER> | Document version | 
| <CREATION_DATE> | Original creation date | 
| <LAST_REVIEW_DATE> | Most recent review date | 
| <REVIEWER_ROLE_OR_TITLE> | Role or title of reviewer | 
| <APPROVAL_BODY> | Approving authority | 
| <APPROVAL_DATE> | Date of formal approval | 
| <REVIEW_PERIOD> | Review interval | 
| <POLICY_WEIGHT> | Ordering/priority value | 
| <ISMS_NAME> | Name of ISMS | 
| <ISMS_SCOPE_DOCUMENT> | Scope document title |
| <SECURITY_MONITORING_ROLE> | Role responsible for monitoring | 
| <SYSTEM_ADMIN_ROLE> | Role managing systems | 
| <DATA_RETENTION_POLICY> | Data retention policy reference | 
| <SIEM_PLATFORM> | SIEM or monitoring tool | 
| <INCIDENT_MANAGEMENT_PROCEDURE> | Incident handling procedure | 
| <INCIDENT_TRACKING_SYSTEM> | Incident tracking tool | 
| <SECURITY_OPERATIONS_FUNCTION> | Security operations team or function |
| <TIME_SYNCHRONISATION_STANDARD> | Time sync standard |






