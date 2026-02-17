# Gap Summary

## Overview
This document outlines configuration deviations identified during the 
Windows 11 v24H2 Security Baseline comparison using Policy Analyzer.

---

## Identified Deviations

### 1. Minimum Password Length
- **Current Setting:** 0
- **Baseline Recommendation:** 14
- **Status:** Non-Compliant

A minimum password length of 0 allows extremely weak passwords, 
significantly increasing brute-force susceptibility.

---

### 2. Password Complexity
- **Current Setting:** Disabled
- **Baseline Recommendation:** Enabled
- **Status:** Non-Compliant

Password complexity requirements were not enforced, allowing simple 
and easily guessable passwords.

---

### 3. Password History
- **Current Setting:** 0
- **Baseline Recommendation:** 24
- **Status:** Non-Compliant

Password reuse was not restricted, increasing risk of credential reuse attacks.

---

### 4. Service Configuration Deviations
Certain services deviated from the Microsoft baseline configuration.

These deviations may increase attack surface if unnecessary services are enabled.
