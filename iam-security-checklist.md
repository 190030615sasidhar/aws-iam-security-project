# AWS IAM Security Checklist

## Identity and Access Management
- Create individual IAM users instead of sharing root credentials
- Enable MFA for all users
- Apply least privilege access
- Use IAM groups for permission management
- Review user permissions regularly
- Remove unused users and access keys
- Avoid using root account for daily tasks

## Password and Access Key Security
- Enforce strong password policy
- Rotate access keys regularly
- Disable inactive access keys
- Monitor failed login attempts
- Avoid hardcoding credentials in code

## Monitoring
- Enable AWS CloudTrail
- Review IAM activity logs
- Monitor privilege changes
- Track failed authentication attempts

## Security Review Questions
- Are all users assigned only the permissions they need?
- Is MFA enabled for all privileged users?
- Are inactive users removed?
- Are access keys rotated regularly?
- Are root account credentials protected?
