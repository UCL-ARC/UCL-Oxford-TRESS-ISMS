---
title: "<DOC_TITLE>"
weight: <DOC_WEIGHT>
---

# <ORG_NAME> – <ISMS_NAME> Access Control Policy


**Document Name:** <DOCUMENT_ID>

**Author:** <AUTHOR_NAME>

**Classification:** <DOCUMENT_CLASSIFICATION> 

**Version:** <VERSION_NUMBER>

**Last Review:** <LAST_REVIEW_DATE>

**Last Reviewed by:** <REVIEWER_NAME>

**Approved by:** <APPROVER_NAME_OR_BOARD>

**Approved date:** <APPROVAL_DATE>

**Review Period:** <REVIEW_PERIOD>

**Sources:** <REFERENCE_DOCUMENTS_OR_LINKS>


## 1.	Document Overview
This Access Control Policy establishes the requirements to ensure the protection of Trusted Research Environments (TREs) within the scope of <ORG_NAME>’s Information Security Management System (ISMS) by managing access rights. This policy supports compliance with relevant standards (e.g., ISO 27001), ensuring that access to information is based on business needs and aligned with security requirements.

This document covers:

- [Access Control Principles](#4-access-control-principles)
- [User Access Management](#5-user-access-management)
- [Authentication Principles](#6-authentication-principles)
- [Privileged Access Management](#7-privileged-access-management)
- [Physical Access](#8-physical-access)
- [Network Access](#9-network-access)
- [Operating System Access](#10-operating-system-access)
- [Information System Access](#11-information-system-access)
- [Monitoring and Logging](#12-monitoring-and-logging)


## 2.	Document Scope
This policy applies to all employees, contractors, consultants, temporary staff, service accounts, and any other individuals with access to Trusted Research Environments. The scope includes infrastructure, applications, and services that support the TREs, referred to in this document as “information systems”.


## 3.	Conventions used in this Document

|Term|Definition|
|----|----------|
|Shall| A mandatory requirement of this policy |
|Should| A recommended requirement of this policy |
|May| An optional requirement of this policy |

## 4.	Access Control Principles
Access to information systems shall be managed according to the following principles:

- **Need to Know:** Access shall be granted based on the specific tasks a user must perform or a system account is designated for.
- **Least Privilege:** Accounts shall be granted the minimum permissions necessary to perform their roles.
- **Role-Based Access Control (RBAC):** Access rights shall be assigned according to defined roles within the organisation.
- **Segregation of Duties:** No individual shall have control over all aspects of any critical system or process.

## 5.	User Access Management
All user access shall be managed by an appropriate role as described in the <ORG_NAME> roles and responsibilities framework.

- **User registration, de-registration, and access authorisation:** Formal procedures for adding, changing, or removing user access shall be implemented.
  - New users or changes to user access shall be approved by:
    - The Information Asset Owner or Information Asset Administrator (for a project or study)
    - TRE Environment Owner (for infrastructure and code management)
    - Supporting the Service Owner or their delegate (for IT service access)
- **Removal of access rights:** Access shall be removed promptly upon termination or role change.
- **Review of access rights:** Periodic reviews of user access rights should be conducted at least once per operational cycle to ensure appropriateness.

## 6.	Authentication Principles
All users and systems shall comply with <ORG_NAME>’s authentication standards and policies, including multi-factor authentication where required.

## 7.	Privileged Access Management
Administrative or privileged accounts shall be tightly controlled and limited to authorised personnel. Privileged accounts should be used only for administrative purposes. Privileged access management shall follow a formal process that grants only the minimum privileges necessary to perform the assigned role or task. A formal record of all allocated privileges shall be maintained.


## 8.	Physical Access
Physical access shall be granted only upon the authority of the facility owner or service manager. All physical information systems shall be protected in accordance with their value and classification per <ORG_NAME>’s information management policies. Approved personnel shall be responsible for physical security measures to prevent unauthorised access to devices or data.

## 9.	Network Access
- Diagnostic and configuration ports shall be enabled only for approved business reasons.
- All unused ports shall be disabled or removed.
- Changes to network configuration affecting TRE networks shall be risk assessed and recorded.
- Network segregation shall be implemented according to risk assessments to protect sensitive information.

## 10. Operating System Access
- Users shall authenticate as authorised users at log-on.
- Passwords shall be managed in accordance with <ORG_NAME> password policies, including periodic changes.
- Sessions shall automatically lock after periods of inactivity.
- Default operating system accounts shall be disabled, deleted, or have default passwords changed upon system deployment.

## 11. Information System Access
- Accounts without adequate assurance shall be disabled until appropriate verification is provided.
- Removal of accounts shall include removal of associated access rights.
- TRE Environment Owners shall implement appropriate segregation of information assets on networks.

Environment Owners shall group information assets as appropriate to achieve the required network segregation.

## 12.	Monitoring and Logging
Access to TREs shall be logged and monitored for security incident investigation purposes. Logs should include a timestamp, the user's identity, and the reason for access. Periodic reviews shall detect unauthorised access attempts. Any anomalies or violations shall be assessed and reported as information security incidents in accordance with <ORG_NAME> incident management procedures.


## Placeholder Reference
| Placeholder | Description |
|-------------|-------------|
| <ORG_NAME> | Name of the organisation or institution |
| <TRE_POLICY_NAME> | Name of the policy |
| <AUTHOR_NAME> | Name of policy author or responsible team |
| <DOCUMENT_CLASSIFICATION> | Sensitivity of document | 
| <VERSION_NUMBER> | Current document version |
| <LAST_REVIEW_DATE> | Date the policy was last reviewed |
| <REVIEWER_NAME> | Name of individual reviewing the policy |
| <APPROVER_NAME_OR_BOARD> | Name of approving authority (CISO, Board, etc.) |
| <APPROVAL_DATE> | Date the policy was approved |
| <REVIEW_PERIOD> | Period after which policy must be reviewed |
| <REFERENCE_DOCUMENTS_OR_LINKS> | Any relevant source documents, standards, or guidance links |


