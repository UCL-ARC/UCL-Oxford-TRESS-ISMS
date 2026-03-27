---
title: "<DOC_TITLE>"
weight: <DOC_WEIGHT>
---
# <ORG_NAME> Information Security Management System Policy 


**Document Name:** <DOC_ID>  

**Classification:** <DOCUMENT_CLASSIFICATION>  

**Version:** <VERSION_NUMBER>  

**Created:** <CREATED_DATE>  

**Last Review:** <LAST_REVIEW_DATE>  

**Approved by:** <APPROVING_BODY>  

**Approval Date:** <APPROVAL_DATE>  

**Review Period:** <REVIEW_PERIOD> 

## 1. Document Overview

This document defines the approach to **data classification** and **environment tiering** for data within the scope of the <ISMS_NAME>.

An “Environment” refers to a technical architecture composed of applications, infrastructure, and services used to store and process information.

This policy defines the process through which data is:
- Classified according to sensitivity and impact
- Assigned to an Environment Tier
- Stored and processed in an environment of the appropriate tier (or higher)

The objective is to ensure that data is stored and processed within environments that provide **proportionate and appropriate security controls**.


### This document covers:

- Policy Scope  
- Related Policies and Documents  
- Environment Tiers and Data Classification  
- Environment Tier Definitions  
- Assigning a Tier to an Environment  
- Data Classification and Tiering Process  


### ISO/IEC 27001 Alignment

This document supports compliance with:

- **ISO/IEC 27001:2022 – Clause 6.1**


### 1.1 Terminology and Conventions

| Term | Definition |
|------|------------|
| **Shall** | Mandatory requirement |
| **Should** | Recommended requirement |
| **May** | Optional requirement |


## 2. Policy Scope

This policy applies to all data within the scope of the <ISMS_NAME>.

Only data that has been:
- Classified, **and**
- Assigned to an Environment Tier  

Is considered **within scope** of the ISMS.

Data processed in unclassified or non-tiered environments shall be considered **out of scope** unless formally approved and documented.

This policy aligns with the organisation’s primary information classification scheme as defined in:

> <INFORMATION_MANAGEMENT_POLICY_NAME>

Assigning classified data to a technical Environment Tier refines the **Confidentiality** dimension.  
**Integrity** and **Availability** are addressed separately via the risk management process.



## 3. Related Policies and Documents

- <INFORMATION_MANAGEMENT_POLICY_NAME>  
- <RISK_LIKELIHOOD_AND_IMACT_GUIDANCE>  
- <ROLES_AND_RESPONSIBILITIES_POLICY>  


## 4. Environment Tiers and Data Classification

| Classification Level | Environment Tier | Trusted Environment | In ISO 27001 Scope |
|---------------------|------------------|---------------------|---------------------|
| <CLASSIFICATION_1> | Tier 4 | Yes | Yes |
| <CLASSIFICATION_1> | Tier 3 | Yes | Yes |
| <CLASSIFICATION_1> | Tier 2 | No  | No  |
| <CLASSIFICATION_2> | Tier 1 | No  | No  |
| <CLASSIFICATION_3> | Tier 0 | No  | No  |

### Tier Overview

- Tier 3 and Tier 4 environments are defined as **<TRUSTED_ENVIRONMENT_NAME>** and fall within ISO 27001 certification scope.  
- Tier 2 environments may handle high-impact data under tightly controlled conditions.
- Tier 1 environments handle moderate sensitivity data.
- Tier 0 environments handle public or unrestricted data.



## 4.1 Data Classification and Tiering Process

Data shall be classified during the creation or onboarding process.

The **Information Asset Owner** shall:
- Be accountable for data classification  
- Consider legal, regulatory, ethical, and contractual requirements.  



## 4.2 Safe Data

Data may be transformed (e.g., pseudonymised or anonymised) using recognised frameworks such as the **<SAFE_DATA_FRAMEWORK>** and reclassified accordingly.

Once reclassified, it may be eligible for storage in a lower-tier environment.

Accountability remains with the **Information Asset Owner**, while operational responsibility resides with the delivery team under the <SHARED_RESPONSIBILITY_MODEL_NAME>.



## 4.3 Safe Outputs

When outputs are exported from a **Trusted Environment**, they must be reviewed and approved to ensure compliance with safe data release principles.

The Information Asset Owner remains accountable for ensuring the safety of the output.



## 4.4 Data Labelling

All classified data shall be labelled with:
- Confidentiality level
- Integrity level
- Availability level
- Required Environment Tier

These labels shall be:
- Embedded in metadata where possible
- Maintained and kept accurate throughout the data lifecycle



## 5. Environment Tier Definitions

### 5.1 Tier 4

| Attribute | Value |
|---------|------|
| Classification | <CLASSIFICATION_1> |
| Within ISO Scope | Yes |
| Trusted Environment | Yes |

Tier 4 environments shall be used where:

- Legal or contractual obligations require a trusted environment  
- Impact rating is **High or Critical**  
- Data includes highly sensitive personal or regulated information  
- There is a likelihood of targeting by advanced threat actors



### 5.2 Tier 3

| Attribute | Value |
|---------|------|
| Classification | <CLASSIFICATION_1> |
| Within ISO Scope | Yes |
| Trusted Environment | Yes |

Tier 3 environments should be used where:

- Data is highly sensitive  
- Impact rating remains high  
- There is no credible evidence of advanced targeted threat actors  



### 5.3 Tier 2

| Attribute | Value |
|---------|------|
| Classification | <CLASSIFICATION_1> |
| Within ISO Scope | No |
| Trusted Environment | No |

Tier 2 may be used where:

- Data has been effectively pseudonymised  
- Re-identification risk is assessed as low  
- Legal and contractual obligations permit such processing  



### 5.4 Tier 1

| Attribute | Value |
|---------|------|
| Classification | <CLASSIFICATION_2> |
| Within ISO Scope | No |
| Trusted Environment | No |

Tier 1 environments handle moderate sensitivity data where:

- Impact rating is medium  
- Data does not include sensitive personal information  



### 5.5 Tier 0

| Attribute | Value |
|---------|------|
| Classification | <CLASSIFICATION_3> |
| Within ISO Scope | No |
| Trusted Environment | No |

Tier 0 environments handle public or unrestricted data only.



## 6. Assigning a Tier to an Environment

Each environment within the ISMS shall be documented in an **Environment Definition Document**.

This document shall define:

- Supported classification levels  
- CIA thresholds  
- Environment boundaries  
- Security controls implemented  

Environment documentation shall be controlled in accordance with the <DOCUMENT_CONTROL_POLICY>.



## 7. Data Classification and Tiering Process Map

> Insert process diagram here:  
> `<PROCESS_DIAGRAM_REFERENCE>`



## Placeholder Reference

| Placeholder | Description |
|------------|------------|
| <ORG_NAME> | Name of organisation |
| <ISMS_NAME> | Name of ISMS or security framework |
| <DOC_TITLE> | Title of the policy |
| <DOC_ID> | Document reference code |
| <VERSION_> | Document version |
| <CREATED_DATE> | Date created |
| <LAST_REVIEW_DATE> | Last review date |
| <APPROVING_BODY> | Committee or body approving policy |
| <APPROVAL_DATE> | Date approved |
| <REVIEW_PERIOD> | Policy review interval |
| <DOCUMENT_CLASSIFICATION> | Sensitivity of document |
| <INFORMATION_MANAGEMENT_POLICY_NAME> | Link or name of classification policy |
| <CLASSIFICATION_1> | Highest classification level |
| <CLASSIFICATION_2> | Medium classification level |
| <CLASSIFICATION_3> | Lowest classification level |
| <TRUSTED_ENVIRONMENT_NAME> | e.g. Trusted Research Environment |
| <SAFE_DATA_FRAMEWORK> | Safe data framework name |
| <SHARED_RESPONSIBILITY_MODEL_NAME> | Internal governance model |
| <ENVIRONMENT_DEFINITION_TEMPLATE> | Template or standard used for environment definitions |
| <DOCUMENT_CONTROL_POLICY> | Policy governing document control |
| <PROCESS_DIAGRAM_REFERENCE> | Reference/link to your diagram |


