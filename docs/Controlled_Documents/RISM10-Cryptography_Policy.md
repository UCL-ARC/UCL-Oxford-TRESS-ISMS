---
title: "<DOC_TITLE>"
weight: <DOC_WEIGHT>
---

# <ORG_NAME> – <ISMS_NAME> Cryptography Policy

**Document Name:** <DOCUMENT_ID>  

**Classification:** <DOCUMENT_CLASSIFICATION>  

**Version:** <VERSION_NUMBER>  

**Last Review Date:** <LAST_REVIEW_DATE>  

**Approved by:** <APPROVAL_BODY>  

**Approved Date:** <APPROVAL_DATE>  

**Review Period:** <REVIEW_PERIOD>  

## 1. Scope

This policy defines the minimum requirements for cryptographic controls on information systems within the scope of the <ISMS_NAME>.

This includes cryptographic protection for:

- Data at rest (e.g., files, databases, storage volumes)
- Data in transit (e.g., network communications, API calls, remote access)
- System-to-system communications and user authentication processes



## 2. Conventions Used in This Document

| Term   | Definition                               |
|--------|-------------------------------------------|
| Shall  | A mandatory requirement of this policy    |
| Should | A recommended requirement of this policy  |
| May    | An optional requirement of this policy    |



## 3. Cryptographic Standards

The organisation shall ensure that:

- All cryptographic algorithms, protocols and key lengths meet or exceed current industry best practice and regulatory requirements.  
  Examples include: `<APPROVED_ENCRYPTION_ALGORITHMS>` (e.g., AES-256, RSA-2048, SHA-256).
- All cryptographic implementations comply with the <CRYPTOGRAPHY_STANDARD> and <REGULATORY_REQUIREMENTS>.
- Deprecated, weak or insecure algorithms (e.g., MD5, DES, SHA-1) shall not be used in any system or process.



## 4. Key Management

The organisation shall ensure that:

- Cryptographic keys are securely generated, stored, distributed and destroyed in alignment with the <KEY_MANAGEMENT_POLICY>.
- Keys shall be protected against unauthorised access, modification, disclosure and loss.
- Key rotation shall be performed according to the defined key lifecycle, or immediately following any suspected or confirmed compromise.
- Key management activities shall be logged, monitored and audited.



## 5. Encryption of Data

The organisation shall ensure that:

- All sensitive or confidential data shall be encrypted at rest using approved cryptographic mechanisms.  
  Where encryption is not feasible, approved compensating controls must be implemented and documented.
- All sensitive data shall be encrypted in transit within secure environments such as <SECURE_ENVIRONMENT_NAME>.
- All data transmitted between secure environments and external networks shall be encrypted using approved secure communication protocols.
- Encryption exceptions must be formally approved by the <SECURITY_GOVERNANCE_BODY> and recorded in the risk register.



## 6. Digital Signatures and Certificates

The organisation shall ensure that:

- Digital certificates are managed through a formal lifecycle process including issuance, renewal, revocation and auditing.
- Automated certificate management solutions should be used where practicable.
- Certificate validity, trust chains and expiry dates shall be monitored and regularly reviewed.
- Compromised or expired certificates shall be revoked and replaced without undue delay.



## Placeholder Reference 

| Placeholder | Description |
|------------|--------|
| <ORG_NAME> | Organisation name |
| <ISMS_NAME> | Name of the Information Security Management System |
| <POLICY_CODE> | Policy identifier |
| <POLICY_TITLE> | Policy title |
| <DOC_WEIGHT> | Document ordering index |
| <DOCUMENT_ID> | Internal document identifier |
| <DOCUMENT_CLASSIFICATION> | Sensitivity of document |
| <VERSION_NUMBER> | Policy version |
| <LAST_REVIEW_DATE> | Most recent review date |
| <APPROVAL_BODY> | Approving authority or governance body |
| <APPROVAL_DATE> | Date of approval |
| <REVIEW_PERIOD> | Policy review interval |
| <APPROVED_ENCRYPTION_ALGORITHMS> | List of approved encryption algorithms |
| <CRYPTOGRAPHY_STANDARD> | Cryptographic standard (e.g. NIST, ISO, NCSC) |
| <REGULATORY_REQUIREMENTS> | Applicable legal/regulatory obligations |
| <KEY_MANAGEMENT_POLICY> | Reference to key management policy or standard |
| <SECURE_ENVIRONMENT_NAME> | Secure environment name (e.g., TRE, Secure Data Lab) |
| <SECURITY_GOVERNANCE_BODY> | Security governance or risk committee |

