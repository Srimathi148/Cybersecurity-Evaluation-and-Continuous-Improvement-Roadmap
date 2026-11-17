
# Cybersecurity Evidence Collection Procedure

## 1. Purpose

This procedure defines how cybersecurity evidence should be collected, recorded, verified, stored and securely disposed of at Apex Technologies Pvt. Ltd.

## 2. Types of Evidence

- Security monitoring alerts
- Vulnerability assessment reports
- Authentication and access logs
- Incident timelines
- System audit records
- Relevant screenshots
- Backup and recovery records

## 3. Evidence Collection Process

1. Identify the security event or evaluation activity.
2. Assign a unique evidence identification number.
3. Record the date, time and time zone of collection.
4. Record the name or role of the authorised collector.
5. Describe the source system and evidence type.
6. Collect evidence using authorised procedures.
7. Calculate a SHA-256 hash for applicable digital files.
8. Record the hash in the evidence register.
9. Store evidence in an approved, access-controlled location.
10. Maintain a record of evidence access and transfers.
11. Review retention requirements and securely dispose of expired evidence when authorised.

## 4. Evidence Register Fields

The evidence register should include:

| Field | Description |
|---|---|
| Evidence ID | Unique evidence reference |
| Evidence Type | Log, screenshot, report or other record |
| Source | System or location from which evidence originated |
| Collection Date | Date and time of collection, including time zone |
| Collected By | Authorised collector's role |
| SHA-256 Hash | Complete 64-character hexadecimal digest, where applicable |
| Storage Location | Approved secure storage reference |
| Access History | Record of authorised access or transfer |
| Retention Status | Active, under preservation or eligible for disposal |

## 5. Integrity Verification

A SHA-256 hash may be calculated when evidence is collected and recalculated when its integrity needs to be verified.

If the calculated hash differs from the recorded hash, the discrepancy must be investigated and documented.

A hash helps verify file integrity; it does not independently prove that the evidence is authentic or that its collection was authorised.

## 6. Chain of Custody

Every evidence transfer must record:

- Evidence ID
- Person releasing the evidence
- Person receiving the evidence
- Date and time of transfer
- Reason for transfer
- Integrity verification result

## 7. Secure Storage and Access

Evidence must be stored in approved, access-controlled locations. Access should be limited to authorised personnel and recorded where appropriate.

Sensitive evidence must never be uploaded to public GitHub repositories, public cloud folders or unencrypted email.

## 8. Retention and Disposal

Evidence must be retained according to the organisation's approved retention schedule and applicable legal, regulatory, contractual and incident-specific preservation requirements.

Evidence under investigation or legal preservation must not be deleted without proper authorisation. Expired evidence must be securely disposed of, with disposal documented.

## 9. Disclaimer

This is a proposed academic procedure for a hypothetical organisation. The examples do not represent actual production evidence or a real security incident.
