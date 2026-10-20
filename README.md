CS 305: Software Security Portfolio

Artemis Financial – Practices for Secure Software

1. Client and Software Requirements

Artemis Financial is a financial consulting company that needed assistance improving the security of its software application. The company wanted to protect sensitive financial information and ensure its application followed secure coding practices. My responsibility was to identify potential vulnerabilities, implement security improvements, and verify that the application continued to function correctly.

2. Identifying Vulnerabilities and the Importance of Secure Coding

One thing I did well during this project was using vulnerability assessment tools to identify potential security risks. I used OWASP Dependency-Check with Maven to examine the application's dependencies for known vulnerabilities. Secure coding is important because it protects customer information, reduces security risks, and helps prevent unauthorized access. For a financial company like Artemis Financial, strong software security also helps maintain customer trust and protects the company's reputation.

3. Challenges During the Vulnerability Assessment

One of the more challenging parts of this project was working with Maven and understanding the vulnerability assessment results. I had to learn how dependencies could introduce security risks, even when the application appeared to function correctly. This experience helped me understand the importance of reviewing security reports and identifying which vulnerabilities need attention.

4. Increasing Layers of Security

I increased the application's security by implementing SHA-256 hashing and configuring HTTPS using SSL/TLS. SHA-256 was used to generate a checksum, while HTTPS helped secure communication between the application and the client. In future projects, I would continue using OWASP Dependency-Check, security testing, and code reviews to identify potential vulnerabilities. I would also evaluate the severity of each vulnerability before deciding which security improvements were necessary.

5. Testing Application Functionality and Security

After making changes to the application, I tested it to make sure everything continued to function correctly. I used Eclipse and Maven to build and run the application. I also tested the HTTPS endpoint to verify that it returned the expected SHA-256 checksum information. I performed dependency checks to identify known security vulnerabilities. Some vulnerabilities were reported, and an issue updating the vulnerability database limited the assessment results. This taught me that developers must continue testing and reviewing security risks even after an application is running successfully.

6. Resources, Tools, and Coding Practices

Throughout this project, I used several tools, including Eclipse, Java, Maven, OWASP Dependency-Check, and the Java MessageDigest class. These tools helped me understand how to build, test, and secure Java applications. I also gained experience working with HTTPS certificates and reviewing security vulnerabilities. These skills will be useful in future programming assignments and professional software development projects.

7. Demonstrating Skills to Future Employers

I would show future employers my Artemis Financial Practices for Secure Software Report because it demonstrates my ability to identify vulnerabilities, implement security improvements, and test application functionality. This project also highlights my experience using Java, Maven, Eclipse, SHA-256 hashing, and HTTPS. Most importantly, it demonstrates my understanding of why software security is important and how developers can help protect applications and sensitive information.

Skills Demonstrated

Java application development
Secure coding practices
Software vulnerability assessment
OWASP Dependency-Check
Maven project management
SHA-256 checksum generation
HTTPS and SSL/TLS configuration
Application testing and troubleshooting
Software security documentation

Portfolio Artifact

Artemis Financial – Practices for Secure Software Report (Project Two)

This report documents the security improvements and testing performed on the Artemis Financial application. It demonstrates my understanding of software security practices and the importance of protecting sensitive financial information.
