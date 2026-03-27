---
title: "<DOC_TITLE>"
weight: <DOC_WEIGHT>
---

# <ORG_NAME> – <ISMS_NAME> Backup and Restore Policy

**Document Name:** <DOCUMENT_ID>  

**Classification:** <DOCUMENT_CLASSIFICATION>

**Version:** <VERSION_NUMBER>  

**Last Review Date:** <LAST_REVIEW_DATE>  

**Approved by:** <APPROVAL_BODY>  

**Approved Date:** <APPROVAL_DATE>  

**Review Period:** <REVIEW_PERIOD> 

## 1. Scope

This policy defines the minimum requirements for the backup and restoration of information systems and data that fall within the scope of the <ISMS_NAME>.

Copies of research data stored in **Low** or **Medium Availability Environments** (as defined in the <AVAILABILITY_CLASSIFICATION_SCHEME>) do not require backup unless otherwise mandated by regulatory, contractual, or operational requirements.



## 2. Conventions Used in This Document

| Term   | Meaning                                  |
|--------|------------------------------------------|
| Shall  | A mandatory requirement of this policy   |
| Should | A recommended requirement of this policy |
| May    | An optional requirement                  |



## 3. Backup Requirements

The organisation shall ensure that backup processes are implemented and maintained in accordance with the following requirements:

- Backups shall be stored in a geographically separate location from the originating systems.
- Backup storage locations shall be secure, environmentally protected and access-controlled.
- All backup data containing sensitive or confidential information shall be encrypted in accordance with the <ENCRYPTION_STANDARD>.
- Backup integrity shall be verified regularly to ensure data is complete, uncorrupted and recoverable.
- Automated monitoring and periodic test restores shall be conducted to validate backup processes.
- Daily and incremental backups shall be retained for a minimum of <DAILY_BACKUP_RETENTION_PERIOD>.
- Weekly backups shall be retained for a minimum of <WEEKLY_BACKUP_RETENTION_PERIOD>.
- After the retention period expires, backups shall be securely deleted within <BACKUP_DELETION_PERIOD>.



## 4. Restore Requirements

The organisation shall ensure that restore operations meet the following requirements:

- Requests for restoration of research data shall only be approved by the <INFORMATION_ASSET_OWNER> or <INFORMATION_ASSET_ADMINISTRATOR>.
- System-level restorations shall only be approved by the <ENVIRONMENT_OWNER> or authorised system administrators.
- Research data shall only be restored to an environment of an equivalent or higher classification tier (as defined in the <ENVIRONMENT_CLASSIFICATION_STANDARD>).
- Access controls and classification markings shall remain enforced following restoration.
- Backup restore testing shall be performed at least every <RESTORE_TEST_FREQUENCY>.



## Placeholder Reference 

| Placeholder | Definition |
|------------|--------|
| <ORG_NAME> | Organisation name |
| <ISMS_NAME> | Name of the Information Security Management System |
| <POLICY_CODE> | Policy identifier (e.g., RISM09) |
| <POLICY_TITLE> | Policy title |
| <DOC_WEIGHT> | Document ordering weight or index |
| <DOCUMENT_ID> | Internal document identifier |
| <DOCUMENT_CLASSIFICATION> | Sensitivity of document |
| <VERSION_NUMBER> | Policy version |
| <LAST_REVIEW_DATE> | Date of most recent policy review |
| <APPROVAL_BODY> | Approving authority or governance body |
| <APPROVAL_DATE> | Approval date |
| <REVIEW_PERIOD> | Policy review interval |
| <AVAILABILITY_CLASSIFICATION_SCHEME> | Organisational availability classification scheme |
| <ENCRYPTION_STANDARD> | Encryption standard or policy reference |
| <DAILY_BACKUP_RETENTION_PERIOD> | Daily/incremental backup retention period |
| <WEEKLY_BACKUP_RETENTION_PERIOD> | Weekly backup retention period |
| <BACKUP_DELETION_PERIOD> | Backup deletion timeframe after retention expiry |
| <INFORMATION_ASSET_OWNER> | Role responsible for data ownership |
| <INFORMATION_ASSET_ADMINISTRATOR> | Role responsible for managing information assets |
| <ENVIRONMENT_OWNER> | System or environment owner |
| <ENVIRONMENT_CLASSIFICATION_STANDARD> | Environment security classification framework |
| <RESTORE_TEST_FREQUENCY> | Frequency of restore test exercises |
