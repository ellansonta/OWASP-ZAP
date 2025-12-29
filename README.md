# OWASP-ZAP
This lab demonstrates a safe, controlled assessment of DVWA using OWASP ZAP. The goal is to Configure ZAP to proxy your browser traffic Spider the application to discover endpoints Run Active Scan to probe for common vulnerabilities Review Alerts, validate findings, and capture a clean HTML/PDF report
Lessons Learned


Importance of Controlled Environments
Always perform vulnerability testing in isolated labs to avoid legal and ethical issues.


Proxy Configuration Matters
Misconfigured browser proxy or missing ZAP CA certificate can block traffic and scans.


Authentication Handling is Critical
Without proper context and login configuration, authenticated areas remain untested.


Spidering Before Active Scan
A thorough spidering phase ensures ZAP discovers all endpoints, improving scan coverage.


Alert Validation
Automated findings need manual verification—false positives are common in security tools.


DVWA Security Levels Affect Results
Higher security levels require more advanced techniques; start low for learning, then scale up.


Reporting for Stakeholders
Clean, structured reports (HTML/PDF) help communicate findings and remediation steps effectively.


Continuous Learning
Tools like OWASP ZAP evolve—staying updated and practicing regularly is key for security engineers.
