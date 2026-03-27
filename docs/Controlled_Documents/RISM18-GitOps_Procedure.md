---
title: "<DOC_TITLE>"
weight: <DOC_WEIGHT>
---

# <ORG_NAME> – <ISMS_NAME> GitOps Change Management Procedure Policy

**Document Name:** <DOCUMENT_ID>

**Classification:** <DOCUMENT_CLASSIFICATION> 

**Version:** <VERSION_NUMBER>  

**Last Review:** <LAST_REVIEW_DATE>  

**Last Reviewed by:** <REVIEWER_ROLE_OR_GROUP>  

**Approved by:** <APPROVAL_BODY>  

**Approval Date:** <APPROVAL_DATE>  

**Review Period:** <REVIEW_PERIOD> 

## 1. Document Overview

This procedure defines how operational and technical changes are managed using Git-based workflows ("GitOps") in accordance with the <CHANGE_MANAGEMENT_POLICY_NAME>.

It applies GitOps practices to ensure:
- Traceability of changes  
- Appropriate authorisation and approvals  
- Repeatable, auditable deployments  
- Alignment with the organisation’s information security controls.



## 2. Scope

This procedure applies to all changes to:

- Documented information  
- Systems and applications  
- Infrastructure and configuration artifacts  

managed through Git-based workflows across all in-scope environments of the <ISMS_NAME>, including:
- Production environments  
- Pre-production or staging environments  
- Testing and development environments  



## 3. GitOps Process

All Git repositories supporting production or pre-production systems shall be hosted in <GIT_PLATFORM> under an organisation or namespace managed by <ORG_NAME>.

Access control shall be enforced so that only authorised roles can:
- Create or merge Pull Requests  
- Approve changes  
- Trigger deployments  



## 4. Change Workflow

Change Requests shall be managed using the following GitOps process.



### 4.1 Issue Creation

All changes shall be initiated using an Issue in <ISSUE_TRACKING_SYSTEM> (e.g. GitHub/GitLab Issues).  
Each Issue shall clearly define the **purpose and context** of the requested change.

Change types shall be classified using labels:

- **Standard Change:** `change-type:standard`  
- **Emergency Change:** `change-type:emergency`  
- **Normal Change:** No specific label required  



### 4.2 Branch Protection Settings

The default branch and any production deployment branch shall enforce:

- Mandatory Pull Requests before merging  
- A minimum of <MINIMUM_APPROVALS> approval(s)  
- Automatic dismissal of stale approvals after new commits  



### 4.3 Pull Request Requirements

If an Issue results in a code or configuration change:
1. A new branch shall be created from the default branch.  
2. The change shall be committed and pushed to <GIT_PLATFORM>.  
3. A Pull Request (PR) shall be raised.

The PR must demonstrate alignment with change management requirements:

| Change Requirement | Implementation in GitOps |
|---------------------|--------------------------|
| Purpose | Linked Issue ID and description |
| Scope | File-level and code/config diff in PR |
| Impact | Included for HIGH impact changes |
| Risk Assessment | Included or linked in PR description |
| Schedule | Specified or referenced in PR description |
| Test Plan | Tests or validation steps included |
| Communication Plan | Documented or linked |
| Rollback Plan | Default rollback via Git revert unless specified otherwise |
| Authorisation | Pull Request approvals |



### 4.4 Impact Classification and Approvals

The impact of a change shall be classified as:

#### HIGH Impact
Changes that significantly affect system security, availability, or service functionality.

- Must be approved by the <ENVIRONMENT_OWNER_ROLE>  
- Approval must include a comment summarising:
  - Security considerations  
  - Stakeholder input  
  - Risk implications

#### Standard / Low Impact
Changes that do not significantly affect system risk or availability.

- May be approved by the <ENVIRONMENT_DEVELOPER_ROLE>

Changes affecting risk levels shall be assessed in line with the <RISK_MANAGEMENT_PROCEDURE> and, if required, escalated to the <RISK_GOVERNANCE_BODY>.

Emergency changes must be retrospectively reviewed and approved by the <ENVIRONMENT_OWNER_ROLE>.



### 4.5 Testing and Validation

All changes shall be tested before production deployment:

- Normal changes shall be tested in <PRE_PRODUCTION_ENVIRONMENT>  
- Emergency changes should be tested where feasible  
- Live production data shall not be used in non-production environments  
- Automated testing shall be implemented where possible  
- Security-critical changes may require:
  - Vulnerability scanning  
  - Security testing  
  - Penetration testing  



## 5. Compliance and Audit

All GitOps activities shall ensure:

- Full traceability of changes  
- Auditability of approvals and decision points  
- Alignment with internal and external compliance requirements  

Git repositories, issues, and pull requests shall serve as official change records.



## Placeholder Reference 

| Placeholder | Description | 
|------------|------------|
| <ORG_NAME> | Name of organisation | 
| <GITOPS_PROCEDURE_NAME> | Name of the GitOps procedure | 
| <GITOPS_PROCEDURE_CODE> | Document identifier | 
| <DOCUMENT_CLASSIFICATION> | Sensitivity of document |
| <VERSION_NUMBER> | Policy version | 
| <LAST_REVIEW_DATE> | Most recent review date | 
| <REVIEWER_ROLE_OR_GROUP> | Role/group that reviewed document | 
| <APPROVAL_BODY> | Approving authority | 
| <APPROVAL_DATE> | Date of approval | 
| <REVIEW_PERIOD> | Scheduled review interval | 
| <POLICY_WEIGHT> | Document ordering value | 
| <ISMS_NAME> | Name of your ISMS | 
| <CHANGE_MANAGEMENT_POLICY_NAME> | Change management policy reference | 
| <GIT_PLATFORM> | Git hosting platform | 
| <ISSUE_TRACKING_SYSTEM> | Issue tracking tool | 
| <MINIMUM_APPROVALS> | Number of required approvals | 
| <ENVIRONMENT_OWNER_ROLE> | Role owning the environment | 
| <ENVIRONMENT_DEVELOPER_ROLE> | Role making changes | 
| <RISK_MANAGEMENT_PROCEDURE> | Risk assessment procedure | 
| <RISK_GOVERNANCE_BODY> | Risk oversight group | 
| <PRE_PRODUCTION_ENVIRONMENT> | Pre-production environment name | 

