# Third-Party Identity Risk Register  
_Track and prioritize vendor-related IAM risks._

| Vendor | Access Type | Data Sensitivity | Contractual Controls | Risk Rating | Mitigation |
|---------|--------------|------------------|-----------------------|--------------|-------------|
| Acme Support | SSO to Jira | PII | NDA + DPA + Audit Rights | High | Revalidate access quarterly, add geo-fencing |
| FinBank Audit | Read-only DB access | Financial | MSA + 2FA | Medium | PAM access + session recording |
| CloudOps Vendor | Admin access to Azure tenant | Infrastructure | SOC 2 Report + Contract SLAs | High | Just-in-Time admin + logging |
| HRTech Partners | API access to employee data | PII | DPA + Data Residency Clause | High | Token-based auth + rate limiting |
| Payroll Vendor | File-based data exchange | Payroll | Encrypted transfer + NDA | Medium | Automate SFTP and audit trail |
| Consulting Firm | Read-only app access | Internal Data | NDA | Low | Restrict to least privilege |
| Software Integrator | Access to staging environment | Internal | Security Addendum | Medium | Monitor with SIEM + PAM proxy |
