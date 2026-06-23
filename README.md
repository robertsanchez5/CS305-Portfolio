# CS 305 Portfolio Artifact Reflection

## Artemis Financial Client Summary
Artemis Financial is a financial services company that required improvements to the security of its web application. The company wanted to ensure that sensitive client information was protected during transmission and storage. The primary issue addressed was implementing secure communications, generating certificates, and verifying data integrity through the use of SHA-256 hashing.

## Software Security and Vulnerability Assessment
I was successful in identifying potential software vulnerabilities and implementing secure coding practices. Coding securely is important because it helps protect sensitive information, prevents unauthorized access, and reduces the likelihood of cyberattacks. Strong software security improves customer trust, protects a company's reputation, and helps avoid financial losses caused by security incidents.

## Challenges and Helpful Experiences
The most challenging part of the vulnerability assessment was understanding and resolving dependency-check findings, including determining which vulnerabilities were false positives and which required mitigation. This process was also helpful because it provided experience using industry security tools.

## Increasing Layers of Security
I increased layers of security by enabling HTTPS, generating certificates, implementing SHA-256 checksum verification, and using OWASP Dependency-Check to identify known vulnerabilities. In the future, I would continue using tools such as OWASP Dependency-Check, static code analysis tools, and vulnerability databases to assess risks and select appropriate mitigation techniques.

## Ensuring Functionality and Security
After refactoring the application, I tested the software by running the application locally and verifying that the checksum endpoint produced the expected SHA-256 hash value. I also reran dependency-check scans to ensure that no additional vulnerabilities had been introduced during the refactoring process.

## Resources and Tools Used
Resources and tools that were useful during this project included Maven, Java keytool, OWASP Dependency-Check, Spring Boot, and SHA-256 hashing libraries. These tools and practices will be valuable in future software development and security-related tasks.

## Demonstrating Skills to Future Employers
This assignment demonstrates my ability to assess software vulnerabilities, implement secure communication methods, use security scanning tools, and apply secure coding practices. I could show future employers the completed Artemis Financial report as evidence of my understanding of software security concepts and hands-on experience with security tools.

## AI Usage Statement
Generative AI was used to assist with organizing ideas, improving wording, and reviewing responses. All submitted work was reviewed and edited by the student for accuracy and completeness.
