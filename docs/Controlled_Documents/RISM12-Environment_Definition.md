---
title: "<DOC_TITLE>"
weight: <DOC_WEIGHT>
---

# <ORG_NAME> - <ISMS_NAME> Environment Definition Policy

**Document Name:** <DOCUMENT_ID>

**Classification:** <INFORMATION_CLASSIFICATION>  

**Version:** <VERSION_NUMBER>  

**Last Review Date:** <LAST_REVIEW_DATE>  

**Approved By:** <APPROVING_BODY>  

**Approval Date:** <APPROVAL_DATE>  

**Review Period:** <REVIEW_PERIOD>  

**Status:** <DOCUMENT_STATUS>

## 1. Document Overview

This policy defines the minimum information that shall be documented and maintained for any technical environment within the scope of the <ISMS_NAME>.

The environment documentation shall be owned and maintained by the designated **<ENVIRONMENT_OWNER_ROLE>**, and treated as controlled documented information under the organisation’s ISMS.

The format of the information may vary, but the content requirements defined in this policy shall be met.



## 2. Policy Scope

This policy applies to any technical environment that is classified as a **<TRUSTED_ENVIRONMENT_TYPE>** and falls within the defined scope of the <ISMS_NAME> and any applicable certifications (e.g. <STANDARD_OR_CERTIFICATION>).

All sections of this template shall be completed for each environment.

The completed Environment Definition shall be treated as controlled documented information in accordance with the <DOCUMENT_CONTROL_POLICY_NAME>.



## 3. Environment and Data Classification

The following environmental characteristics shall be formally documented.

Where an environment supports multiple classifications (e.g. for different workloads or availability requirements), this shall be clearly stated.

### 3.1 Environment Confidentiality Tier

The environment shall be assigned a confidentiality tier in line with the organisation’s:

- <DATA_CLASSIFICATION_POLICY_NAME>  
- <ENVIRONMENT_TIERING_POLICY_NAME>



### 3.2 Environment Integrity Classification

The integrity level of data supported by the environment shall be documented using the classifications defined in:

- <INFORMATION_MANAGEMENT_POLICY_NAME>



### 3.3 Environment Availability Classification

The availability level of the environment shall be documented using the availability classifications defined in:

- <INFORMATION_MANAGEMENT_POLICY_NAME>



## 4. Roles and Responsibilities

The following roles shall be identified, named, and described for each environment.  
Any environment-specific responsibilities or variations shall be documented.

Typical roles include:

- <ENVIRONMENT_OWNER_ROLE>  
- <ENVIRONMENT_ADMIN_ROLE>  
- <ENVIRONMENT_DEVELOPER_ROLE>  
- <OTHER_KEY_ROLES>  

Role definitions should align with the organisation’s <ROLES_AND_RESPONSIBILITIES_POLICY_NAME>.



## 5. Documentation

The location, structure, and management of environment documentation shall be defined, including:

- Controlled documents (e.g. policies, procedures, operating guides)  
- Diagrams and system architecture documentation  
- Change records where applicable  
- Access and version control mechanisms  

The location of work instructions shall be documented.  
Work instructions may be excluded from formal document control where appropriate, but their location and ownership must be clear.



## 6. Environment Asset Register

The location and format of the environment's asset register shall be documented.

The asset register shall include:

- Physical assets  
- Virtual assets  
- Applications and services  
- Supporting infrastructure  

Each asset must have:

- A named asset owner  
- Support information  
- Links to relevant maintenance, warranty, or service agreements  



## 7. Supporting Services

All supporting technical and operational services shall be documented, including:

- Hosting services  
- Backup and recovery services  
- Network services  
- Identity and access services  
- Monitoring and security services  

Where a service is already documented elsewhere, please feel free to provide a reference.

Where additional controls or contractual requirements have been applied, these must be recorded.



## 8. Technical Environment Description

The technical environment shall be fully described using text and diagrams.

This shall include, but is not limited to:

### 8.1 General Description

- Hosting model and location (e.g. cloud provider, on-premise, hybrid)  
- Key technology stack and platforms  
- Virtualisation/containerisation/orchestration model  
- Operating systems and core software components  
- Deployment and implementation approach (e.g. Infrastructure as Code, manual deployment)  
- Physical and logical security boundaries  
- Defined trust boundaries and security zones  
- Standard data flows into, within, and out of the environment  
- Roles catalogue for environment-specific roles (e.g. user types, administrators, project users)



### 8.2 Control-Specific Implementations

Where the environment has specific implementations of information security controls, not fully addressed in earlier sections, these shall be documented here.

This includes:

- Environment-specific control tailoring  
- Compensating controls  
- Technology-specific control implementations  
- Deviations from standard organisational control baselines  

A reference list of applicable ISMS controls shall be maintained, based on:

- <CONTROL_FRAMEWORK_NAME>  
- <STATEMENT_OF_APPLICABILITY_REFERENCE>  



## Placeholder Reference 

| Placeholder | Description |
|------------|-------------|
| <ORG_NAME> | Name of the organisation |
| <ISMS_NAME> | Name of the Information Security Management System |
| <POLICY_CODE> | Internal document reference number |
| <ENVIRONMENT_DEFINITION_POLICY_TITLE> | Title of this policy |
| <INFORMATION_CLASSIFICATION> | Information classification (e.g. Public, Internal, Restricted) |
| <VERSION_NUMBER> | Current document version |
| <LAST_REVIEW_DATE> | Date of last review |
| <APPROVAL_DATE> | Date of approval |
| <APPROVING_BODY> | Body or committee approving the document |
| <REVIEW_PERIOD> | Scheduled review interval |
| <DOCUMENT_STATUS> | Document lifecycle status (e.g. Draft, Approved) |
| <DOC_WEIGHT> | Internal document ordering or numbering weight |
| <ENVIRONMENT_OWNER_ROLE> | Role responsible for owning the environment |
| <ENVIRONMENT_ADMIN_ROLE> | Role responsible for technical administration |
| <ENVIRONMENT_DEVELOPER_ROLE> | Role responsible for development within the environment |
| <OTHER_KEY_ROLES> | Any additional environment roles |
| <TRUSTED_ENVIRONMENT_TYPE> | Type of environment (e.g. Trusted Research Environment, Secure Processing Environment) |
| <STANDARD_OR_CERTIFICATION> | Applicable certification or standard (e.g. ISO/IEC 27001) |
| <DATA_CLASSIFICATION_POLICY_NAME> | Organisation data classification policy |
| <ENVIRONMENT_TIERING_POLICY_NAME> | Environment tiering policy |
| <INFORMATION_MANAGEMENT_POLICY_NAME> | Information management policy |
| <DOCUMENT_CONTROL_POLICY_NAME> | Controlled document management policy |
| <ROLES_AND_RESPONSIBILITIES_POLICY_NAME> | Roles and responsibilities policy |
| <CONTROL_FRAMEWORK_NAME> | Control framework used (e.g. ISO 27001, NIST 800-53) |
| <STATEMENT_OF_APPLICABILITY_REFERENCE> | Reference to the ISMS Statement of Applicability |




