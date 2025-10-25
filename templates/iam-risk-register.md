# IAM Risk Register  
_Aligned with ISO 27001 • SOC 2 • HiTrust_

| Risk ID | Risk Description | Affected IAM Domain | Likelihood | Impact | Current Control | Residual Risk | Recommended Mitigation | Owner |
|----------|------------------|---------------------|-------------|---------|------------------|----------------|------------------------|--------|
| IAM-001 | Stale privileged accounts in CyberArk | Privileged Access | High | High | Manual periodic review | Medium | Implement automated deprovisioning + Just-in-Time access | IAM Ops Lead |
| IAM-002 | Lack of dynamic access reviews | Access Reviews | Medium | Medium | Annual reviews | Medium | Implement risk-based quarterly reviews | Governance Manager |
| IAM-003 | Third-party access not centrally governed | Third-Party Access | High | High | Ad hoc tracking via Excel | High | Implement federated access and contracts with SLAs | IAM Architect |
| IAM-004 | Inconsistent Joiner-Mover-Leaver (JML) processes across regions | Identity Lifecycle | High | High | Manual HR integration | High | Automate JML via HRIS integration and workflow standardization | IAM Program Manager |
| IAM-005 | Unencrypted secrets in CI/CD pipelines | DevOps IAM | High | High | Developer awareness training | Medium | Use vault-based secret management | DevSecOps Lead |
| IAM-006 | Lack of SoD controls in Finance and HR systems | Segregation of Duties | Medium | High | Manual control reviews | Medium | Implement SoD monitoring in IAM tool | Compliance Manager |
| IAM-007 | Orphaned accounts after M&A activities | Identity Lifecycle | Medium | High | Post-merger cleanup checklist | Medium | Integrate identity sources early during M&A | IAM Architect |
| IAM-008 | Weak logging of access changes | Auditability | Medium | Medium | Partial logs in AD | Medium | Centralize IAM audit logging in SIEM | Security Operations Lead |
