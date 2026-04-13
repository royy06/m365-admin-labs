# Security Scenarios

## Scenario 1: Suspicious Login Attempt
User reports login attempts from unknown locations.

### Possible Cause
- Password compromise

### Resolution
- Force password reset
- Enable MFA
- Review sign-in logs in Entra ID

---

## Scenario 2: User Cannot Sign In After MFA Setup
User is locked out after MFA enrollment.

### Possible Cause
- Incorrect MFA setup
- Device not registered properly

### Resolution
- Reset MFA methods in Entra ID
- Re-enroll user in authentication app

---

## Scenario 3: Access Blocked by Policy
User cannot access Microsoft 365 apps.

### Possible Cause
- Conditional Access policy requires compliant device

### Resolution
- Check device compliance status
- Review Conditional Access policy conditions
