# IAM Mini-Project: Azure AD Role Management

**Objective:** Demonstrate user lifecycle management in Azure AD — provisioning, role assignment, remediation, and revocation with audit logs.

## Steps Performed
1. Created test users: `IAM TestAdmin`, `IAM User1`, `IAM User2`.
2. Assigned roles:
   - TestAdmin → User Administrator
   - User1 → Reader
3. Modified privileges:
   - Downgraded TestAdmin from User Administrator → Reader
4. Revoked access:
   - Blocked sign-in for User2
5. Exported Azure AD audit logs for all actions.

## Evidence
- See `/screenshots/` folder for step-by-step screenshots.
- `report.pdf` contains detailed documentation.
- `audit-logs.csv` is exported from Azure AD.

## Key Learnings
- IAM lifecycle involves provisioning, privilege adjustments, and revocation.
- Audit logs provide traceability for compliance and governance.
- Principle of Least Privilege is essential in role assignment.
