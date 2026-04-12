# Conditional Access Policies

## What it is
Conditional Access is a Microsoft Entra ID feature that controls access to applications based on conditions like user location, device, and risk level.

## Common conditions
- User location (country/IP)
- Device compliance
- Sign-in risk level
- Application being accessed

## Common controls
- Require MFA
- Block access
- Require compliant device
- Require trusted location

## Example Policy
If a user signs in from an unknown location, require MFA before allowing access.

## Why it matters
It prevents unauthorized access even if a password is stolen.
