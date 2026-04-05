# Web Application Firewall using ModSecurity & OWASP CRS

## Description
This project demonstrates the implementation of a Web Application Firewall (WAF) using ModSecurity with OWASP Core Rule Set (CRS) to detect and block SQL Injection (SQLi) and Cross-Site Scripting (XSS) attacks.

## Objectives
- Configure Apache with ModSecurity
- Enable OWASP CRS
- Perform attack simulation (XSS, SQLi)
- Analyze logs and detect attacks
- Tune rules to eliminate false positives

## Tech Stack
- Apache2
- ModSecurity v3
- OWASP CRS
- OWASP ZAP
- Ubuntu (WSL2 + QEMU/KVM)

## Key Features
- Detection & blocking of SQLi and XSS attacks
- HTTP 403 response validation
- Log analysis using ModSecurity audit logs
- False positive tuning (Rule ID: 920350)
- Automated scanning using OWASP ZAP

## Attack Simulation
Example payload:
