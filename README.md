# AWS IAM Security Audit

Implemented AWS IAM best practices to secure cloud account - MFA, Least Privilege, and Strong Password Policy.

## What I Did

**1. Created 2 IAM Users:**
- `shraddha-admin` -> Gave only AdministratorAccess
- `shraddha-readonly` -> Gave only ReadOnlyAccess
- This is called Least Privilege Principle

**2. Enabled MFA (Multi-Factor Authentication):**
- Enabled MFA for root account and both IAM users
- Used Google Authenticator

**3. Set Strong Password Policy:**
- Minimum 14 characters
- Requires uppercase, lowercase, numbers, symbols
- Password expires in 90 days

## Why This Is Important?
Without MFA and Least Privilege, anyone can hack AWS account and company can lose lakhs of rupees. This project shows how to secure AWS account like real companies do.

## Proof of Work - Screenshots

![MFA Enabled Proof](./Screenshot_20260412_111528_Chrome.jpg)

**Tools Used:** AWS IAM, MFA, Password Policy

**GitHub:** SH-malvi
