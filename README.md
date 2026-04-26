# Software Security Portfolio Artifact

## Artemis Financial Secure Software Project

Artemis Financial is a financial consulting company that wanted to modernize its web application and improve the security of its client data.  The company required secure communication and a checksum verification step to ensure data integrity during transmission.

During this project, I identified software security vulnerabilities and implemented solutions using secure coding practices.  Coding securely is important because applications that handle financial data must protect against data breaches, unauthorized access, and other security risks.  Strong software security helps maintain customer trust and protects the company from potential threats.

One of the most helpful aspects of this project was using OWASP Dependency-Check to identify vulnerabilities in third-party libraries.  This demonstrated that security risks are not only found in custom code but also in external dependencies.  A challenge was understanding which vulnerabilities were relevant and ensuring no unnecessary changes were made.

I increased layers of security by implementing SHA-256 checksum verification, configuring HTTPS communication, generating a self-signed certificate, and running static analysis tools.  In the future, I would continue using automated tools, manual reviews, and secure coding practices to assess vulnerabilities and determine mitigation strategies.

To ensure the application remained functional and secure, I tested the application after refactoring by verifying the checksum endpoint, confirming HTTPS functionality, and running a secondary dependency-check scan.  This ensured that no new vulnerabilities were introduced.

Tools and resources used in this project include Java, Spring Boot, Maven, Java Keytool, SHA-256 hashing with MessageDigest, HTTPS configuration, and OWASP Dependency-Check.  These tools are valuable for future software development and security-focused tasks.

This project demonstrates my ability to implement secure coding practices, identify vulnerabilities, apply encryption techniques, and validate application security.  It serves as a strong example of my software security skills for future employers.
