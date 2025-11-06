# FUTURE_CS_01 🚩 Task 1: Web Application Security Testing This repository contains my work for Task 1 of the Future Interns Cyber Security Internship.
✅ What You’ll Do
Set up and explore a test web app (like DVWA or OWASP Juice Shop)
Use scanning tools like OWASP ZAP, Burp Suite, or Nikto
Test for common vulnerabilities like SQL injection, XSS, and CSRF
Map the vulnerabilities to OWASP Top 10 threats
Document findings with screenshots, impact level, and remediation steps
Compile a Security Assessment Report (PDF format)

📝 Final Deliverables
PDF Security Report with risk rating, screenshots, and suggestions
OWASP Top 10 Compliance checklist
Tool logs (ZAP scan reports, Burp Suite issues, etc.)
(Optional) Video walkthrough of your findings]


## Introduction

As part of my Cyber Security Internship at Future Interns, I conducted web application security testing on OWASP ZAP. The goal was to identify common web vulnerabilities like - SQL Injection (SQLi), Cross-Site Scripting (XSS), Brute Force Authentication flaws, etc.

This report details my findings, screenshots, and recommended mitigations.



### TASK 1: Set up and explore a test web app (OWASP Juice Shop)
- Before starting anything, I installed docker.io and then used it to lauch the Juice-shop.
- I already have OWASP ZAP installed, so i just lauched it.



### TASK 2: Use scanning tools like OWASP ZAP, Burp Suite, or Nikto (I used OWASP ZAP)
I used OWASP ZAP (2.16.1) on Kali Linux to scan the OWASP Juice-shop application by inputing it's local URL to URL TO ATTACK field and running the automated scan by clicking the ATTACK button. ZAP first crawled the site to discover available pages and then actively tested those pages for vulnerabilities showing the output in the ALERT tabs with certain ratings . I confirmed the findings by copying the suspicious URLs into my browser to see if the issue could be exploited. 
For each confirmed issue, i took screenshots, assessed the harm level and noted key solutions in my report.
