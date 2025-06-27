# CS 305: Software Security Portfolio Artifact

## Artifact: Artemis Financial Practices for Secure Software Report

### Client Overview
Artemis Financial is a fictional financial services company. Their web application was at risk due to poor input validation, lack of access controls, and outdated dependency use. My role was to identify and fix security issues in their Java application.

### What I Did Well
I effectively used OWASP Dependency-Check to identify vulnerable libraries, applied secure coding practices like input validation, SSL configuration, and removed deprecated methods. Secure coding is crucial—it prevents data breaches and helps maintain trust in software systems.

### Challenges and Insights
Balancing functionality with security was challenging. After refactoring, I ran static tests again and validated functionality to ensure no new vulnerabilities were introduced. Learning to evaluate severity and prioritize fixes was especially useful.

### Layers of Security and Future Plans
I improved security by using safe libraries, securing endpoints, and encoding outputs. In future projects, I’d integrate tools like SonarQube or OWASP ZAP for broader scanning and real-time alerts.

### Tools and Practices Used
- OWASP Dependency-Check
- Java's MessageDigest for checksums
- Certificate generation with `keytool`
- Static testing with Maven plugins

### Value for Employers
This project shows my ability to perform real-world vulnerability assessments and apply secure coding principles. It reflects my growing skills in application security and secure development workflows.
