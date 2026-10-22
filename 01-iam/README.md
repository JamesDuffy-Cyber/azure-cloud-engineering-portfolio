# Module 01: Identity & Access Management (IAM)

## 1. Demo Objectives
- Configured user and security group objects within Microsoft Entra ID.
- Evaluated scope boundaries and inheritance between Microsoft Entra ID directory roles and Azure Role-Based Access Control (RBAC).
- Applied least-privilege role assignments at the Resource Group scope.

## 2. Configuration Details
- **Tenant:** Default Entra ID Directory
- **Groups Created:** `secops-tier1-analysts` (Security type, Assigned membership)
- **RBAC Assignment:** Assigned `Reader` role to `secops-tier1-analysts` scoped strictly to `rg-iam-testing`.

## 3. Operational Verification
- Validated that members of `secops-tier1-analysts` inherit Read permissions across resources inside `rg-iam-testing` without receiving subscription-wide or directory-level write privileges.
- [Insert Screenshot 1: Entra ID Group Membership]
- [Insert Screenshot 2: RBAC Role Assignment Blade]

## 4. Teardown
- Removed test users and group from Microsoft Entra ID.
- Deleted test resource group:
  ```azurecli
  az group delete --name rg-iam-testing --yes --no-wait
