# Risk Analysis

## 1. Minimum Password Length = 0

A password length of 0 removes the minimum requirement entirely. 
This allows extremely short passwords (e.g., 1–3 characters).

### Why This Is Dangerous:
- Brute-force attacks become trivial
- Dictionary attacks succeed quickly
- Automated password spraying becomes highly effective

Short passwords drastically reduce entropy and increase compromise probability.

---

## 2. Password Complexity Disabled

Without complexity enforcement, users may create passwords like:
- password
- 123456
- admin

### Why Complexity Matters:
Complexity requirements enforce:
- Uppercase letters
- Lowercase letters
- Numbers
- Special characters

This increases password entropy and resistance to automated attacks.

---

## 3. Real-World Attack Implications

If deployed in an enterprise environment, these misconfigurations could lead to:

- Unauthorized access
- Lateral movement
- Privilege escalation
- Ransomware deployment
- Domain compromise

Weak authentication controls are one of the most common initial access vectors.

---

## Risk Level: HIGH
Authentication policy misconfigurations directly impact system integrity and confidentiality.
