# Windows 11 v24H2 Security Baseline Gap Analysis

## Project Overview
Performed a security gap analysis comparing local host configuration 
against Microsoft Windows 11 v24H2 Security Baseline using Policy Analyzer.

## Tools Used
- Windows 11 v24H2
- Microsoft Security Compliance Toolkit
- Policy Analyzer
- Windows 11 Security Baseline

## Objective
Identify configuration deviations and recommend remediation steps 
to improve system hardening.

## Key Findings
- Minimum password length = 0 (Baseline: 14)
- Password complexity disabled
- Password history not enforced
- Service configuration deviations

## Risk Impact
Weak password policies increase risk of brute force attacks and unauthorized access.

## Remediation
- Enforced 14-character minimum
- Enabled password complexity
- Implemented password history (24)
- Aligned services with baseline

## Report
Full PDF available in /report directory.

## Skills Demonstrated
- Security Baseline Analysis
- Risk Identification
- System Hardening
- Policy Interpretation
- Configuration Management
