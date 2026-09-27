# AWS-IAM-Security-Audit
Implemented IAM best practices- MFA, least privilege , password policy 
# AWS IAM Security Audit & MFA Protection

## Objective
To secure AWS account by implementing IAM security best practices as per AWS Well-Architected Framework.

## What I Did
1. Created 2 IAM Users:
   - shraddha-admin (AdministratorAccess for testing)
   - shraddha-readonly (S3 ReadOnlyAccess - Least Privilege)

2. Enforced MFA:
   - Enabled Virtual MFA for both users using Google Authenticator
   - Screenshot: MFA enabled status

3. Password Policy:
   - Minimum 14 characters
   - Requires uppercase, lowercase, numbers, symbols
   - MFA compulsory

## Tools Used
AWS IAM, AWS MFA, Google Authenticator

## Learning
Understood Least Privilege principle and why MFA is mandatory for cloud security.

## Screenshots
[Add your 3 screenshots here]
