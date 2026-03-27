---
title: "<DOC_TITLE>"
weight: <DOC_WEIGHT>
---

# <ORG_NAME> – <ISMS_NAME> Data Deletion Policy

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

This policy defines the principles and procedures for the secure deletion of data within <ORG_NAME>.  
It ensures that data is erased in a manner that protects confidentiality, integrity, and availability, and complies with all legal, regulatory, and contractual obligations.



## 2. Scope

This policy applies to all information systems and data within the defined scope of the <ISMS_NAME>.  

Reference document: **<ISMS_SCOPE_DOCUMENT>**



## 3. Data Retention and Deletion Criteria

Data retention periods shall be determined by:

- <ORG_NAME> Data Retention Policy  
- Applicable legal and regulatory requirements  
- Relevant contractual obligations with data providers or partners  

Information Asset Owners (<IAO_ROLE>) and Information Asset Administrators (<IAA_ROLE>) shall be responsible for:

- Monitoring applicable retention and contractual requirements  
- Triggering secure deletion when retention periods expire  
- Ensuring deletions align with compliance obligations  



## 4. Secure Deletion (Sanitisation) Methods

At least one of the following sanitisation methods shall be used, in accordance with recognised standards such as **<SANITISATION_STANDARD>** (e.g. NIST 800-88):

- **Clear:** Overwrite user-addressable storage with non-sensitive data  
- **Purge:** Cryptographic erase or firmware-supported secure erase  
- **Destroy:** Physical destruction of storage media  

The selected method shall be proportionate to:
- The classification of the data  
- The type of storage media  
- The assessed risk of data recovery  



## 5. Data Deletion Process – Research / Project Data

1. **Request Initiation**  
   A deletion request shall be initiated by the <IAO_ROLE> or <IAA_ROLE> of the project or data asset.

2. **Approval**  
   The request shall be reviewed and approved by the <DATA_OWNER_ROLE>.

3. **Execution**  
   An authorised administrator shall apply an approved deletion method.

4. **Confirmation**  
   Confirmation shall be recorded that the data has been irreversibly deleted and cannot be reconstructed.



## 6. Data Deletion Process – Information Systems

1. **Change Request Submission**  
   A formal change request shall be raised via the <CHANGE_MANAGEMENT_PROCESS> by a <SYSTEM_ADMIN_ROLE>.

2. **Authorisation**  
   The request shall be approved by the <ENVIRONMENT_OWNER_ROLE>.

3. **Execution**  
   The approved deletion method shall be implemented.

4. **Verification**  
   The deletion shall be verified and confirmed as irreversible.



## 7. Storage Media Destruction

Where logical or cryptographic deletion is not sufficient, physical destruction may be required.

In such cases:

- The decision shall be made by the <ENVIRONMENT_OWNER_ROLE> based on risk.  
- The destruction shall be fully documented.  
- Storage media shall remain under secure custody until destruction.  
- Destruction records shall include serial numbers, dates, and certificates of destruction.  
- Third-party destruction services must be certified to meet <MEDIA_DESTRUCTION_STANDARD> requirements and allow audit rights by <ORG_NAME>.  



## 8. Exceptions and Special Cases

Where data assets are found to be stored in breach of legal or contractual requirements, data may be deleted without express approval from the <IAO_ROLE>.

Such deletions must:

- Be approved by <GOVERNANCE_BODY>  
- Be agreed in consultation with <DATA_PROTECTION_FUNCTION>  
- Be fully documented with justification and risk assessment  



## 9. Records and Evidence

A formal record of all data deletion activities shall be maintained. This shall include:

- Deletion request details  
- Requestor and approver details  
- Method of deletion  
- Date and time of deletion  
- Chain of custody (for physical assets)  
- Serial numbers and destruction certificates (where applicable)  

All records shall be retained in accordance with the <RECORD_RETENTION_POLICY>.



## Placeholder Reference 

| Placeholder | Description | 
|------------|------------|
| <ORG_NAME> | Name of your organisation | 
| <DATA_DELETION_POLICY_NAME> | Title of the policy | 
| <DATA_DELETION_POLICY_CODE> | Internal document identifier | 
| <DOCUMENT_CLASSIFICATION> | Sensitivity of document | 
| <VERSION_NUMBER> | Current document version | 
| <CREATION_DATE> | Initial creation date | 
| <LAST_REVIEW_DATE> | Date of latest review | 
| <REVIEWER_ROLE_OR_TITLE> | Who reviewed the policy | 
| <APPROVAL_BODY> | Approving committee or role | 
| <APPROVAL_DATE> | Date of approval | 
| <REVIEW_PERIOD> | How often policy is reviewed | 
| <ISMS_NAME> | Name of ISMS | 
| <ISMS_SCOPE_DOCUMENT> | ISMS scope document name | 
| <IAO_ROLE> | Information Asset Owner role | 
| <IAA_ROLE> | Information Asset Administrator role | 
| <DATA_OWNER_ROLE> | Data-owning authority | 
| <SYSTEM_ADMIN_ROLE> | Technical administrator role | 
| <ENVIRONMENT_OWNER_ROLE> | Owner of IT environment | 
| <CHANGE_MANAGEMENT_PROCESS> | Change process name | 
| <SANITISATION_STANDARD> | Sanitisation standard | 
| <MEDIA_DESTRUCTION_STANDARD> | Media destruction certification | 
| <GOVERNANCE_BODY> | Governance entity | 
| <DATA_PROTECTION_FUNCTION> | Data protection authority | 
| <RECORD_RETENTION_POLICY> | Records retention policy | 
| <POLICY_WEIGHT> | System ordering priority | 
