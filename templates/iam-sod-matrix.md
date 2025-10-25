# IAM Segregation of Duties (SoD) Matrix  
_Prevent toxic access combinations leading to fraud or abuse._

| Role | Privilege A | Privilege B | SoD Conflict? | Notes |
|-------|---------------|--------------|----------------|--------|
| System Admin | Create Accounts | Approve Access Requests | Yes | Enforce least privilege, separate duties |
| Finance Analyst | Submit Expense Reports | Approve Expense Reports | Yes | Add dual-control mechanism |
| HR Manager | Initiate Hire | Terminate Employee | No | Acceptable risk with periodic review |
| Procurement Officer | Create Vendor | Approve Purchase Order | Yes | Split roles between creator and approver |
| IAM Admin | Modify Role | Approve Access Certification | Yes | Governance control required |
| Security Analyst | Monitor Logs | Close Incidents | No | Reviewed quarterly |
| DevOps Engineer | Deploy Code | Approve Pipeline Changes | Yes | Implement peer review policy |
| Database Admin | Backup DB | Restore DB | No | Controlled through change management |
