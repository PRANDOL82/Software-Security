# Software-Security
Artemis Financial is a financial services provider handling sensitive customer data and transactions. The project involved securing a Spring Boot application through input validation, encrypted communications, secure API interactions, and industry compliance. Vulnerabilities were identified and remediated across architecture, codebase, and dependencies to prevent remote code execution, data leaks, and unauthorized access.

A manual code review and static testing using OWASP Dependency-Check revealed 189 vulnerabilities across 48 dependencies. Critical issues like CVE-2022-1471 (SnakeYAML RCE) and CVE-2022-22965 (Spring4Shell) were prioritized, with targeted upgrades and safe constructors proposed. Secure coding protects user data, prevents breaches, and ensures compliance—essential in finance.

Challenges included managing false positives and verifying suppression logic. A structured flow diagram helped ensure comprehensive coverage from input validation to cryptography.

Security enhancements included upgrading vulnerable libraries (SnakeYAML, Spring Framework, Jackson), disabling risky components (Tomcat AJP connector), and enforcing strict Content Security Policies and input sanitization.

Future strategies involve CI/CD-integrated dependency scanning, continuous CVE monitoring, manual reviews informed by static analysis, and XML suppression with documented justification.

Functionality and security were validated through regression tests, updated scans, error handling and session management reviews, and verification of encryption and key management.

Resources used included OWASP Dependency-Check, secure coding standards, architecture review methodology, XML suppression for audit documentation, and LaTeX for formal reporting.

Portfolio highlights may include a secure Spring Boot application with documented vulnerability mitigation, before-and-after dependency scan screenshots, a formal LaTeX report, and a methodology for suppressing false positives and verifying fixes.
