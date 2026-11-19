# GRC Coursework

Risk assessment, controls, compliance, asset management, and threat modeling exercises based on course scenarios.

## Botium Toys security audit
Reviewed a fictional company's assets, controls, and compliance. Course risk score: 8/10 (high).

**Key gaps:** excessive data access, no least privilege or separation of duties, unencrypted card data, no IDS, no backups or DR plan, weak password policy, no password manager, unmaintained legacy systems.

**Existing controls:** firewall, antivirus, physical access control, CCTV, fire detection.

**Frameworks:** NIST CSF (original five functions; CSF 2.0 adds Govern), PCI DSS, GDPR, SOC 1/2, PII/SPII.

**Recommendations:**
1. Least privilege and separation of duties
2. Restrict access to PII, SPII, and card data
3. Encrypt data in transit and at rest
4. Stronger passwords and central password management
5. Deploy IDS
6. Tested backups and DR plan
7. Legacy system maintenance procedures
8. Regular risk, access, asset, and compliance reviews

Files: [botium-toys-scope-goals-risk-assessment.docx](./botium-toys-scope-goals-risk-assessment.docx), [controls-and-compliance-checklist.docx](./controls-and-compliance-checklist.docx)

## Other exercises
- **Data leak analysis** ([data-leak-worksheet.docx](./data-leak-worksheet.docx)): excess permissions reviewed against NIST SP 800-53 AC-6.
- **PASTA threat model** ([pasta-threat-modeling-worksheet.docx](./pasta-threat-modeling-worksheet.docx)): payment app attack surface, injection and session hijacking, PCI DSS.
- **Hardening risk assessment** ([security-risk-assessment-report.docx](./security-risk-assessment-report.docx)): MFA, password policy, firewall maintenance.
- **Asset inventory** ([home-asset-inventory.xlsx](./home-asset-inventory.xlsx)): assets classified as restricted, confidential, internal, or public.

[← Back to certificate labs](../)
