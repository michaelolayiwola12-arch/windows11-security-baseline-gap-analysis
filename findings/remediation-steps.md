# Remediation Steps

This document outlines how identified gaps were remediated.

---

# Option 1: Local Security Policy (Standalone System)

1. Press Win + R
2. Type: secpol.msc
3. Navigate to:

Security Settings
→ Account Policies
→ Password Policy

4. Configure:
   - Minimum password length: 14
   - Enforce password history: 24
   - Password must meet complexity requirements: Enabled

5. Apply changes and restart if required.

---

# Option 2: Group Policy (Domain Environment)

1. Open Group Policy Management
2. Edit appropriate GPO
3. Navigate to:

Computer Configuration
→ Policies
→ Windows Settings
→ Security Settings
→ Account Policies
→ Password Policy

4. Apply baseline-aligned configurations
5. Run: gpupdate /force

---

# Option 3: PowerShell

Set minimum password length:

net accounts /minpwlen:14

Set password history:

net accounts /uniquepw:24

Verify configuration:

net accounts

---

## Validation

Re-ran Policy Analyzer comparison after remediation.

Result:
All critical password policy deviations resolved.
