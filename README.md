# Report-OWASP-Juice-Shop-challenges
This is a penetration testing report details the findings of a security assessment conducted on OWASP Juice Shop web application.

OWASP Juice Shop is an intentionally insecure web application designed for training, demonstrating, and testing security tools and techniques, encompasses vulnerabilities from the entire OWASP Top Ten along with many other security flaws found in real-world applications.
<img width="1256" alt="screenshot02" src="https://github.com/user-attachments/assets/4cacc9b1-1862-4c1a-9bcc-f8859f2f1c5c">


 Test Scope :
 
The allowed scope for this engagement was the following: OWASP Juice Shop: http://localhost/
The testing team was not provided accounts for testing Methodology


 Test Outcomes:
 
The team uncovered multiple vulnerabilities inside of the web application. The penetration testing team identified critical vulnerabilities that demand immediate attention. The most severe vulnerabilities include Business Logic and Authentication Bypass, both of which pose significant risks to the system's integrity and security. Following these critical issues, the team found several high-risk vulnerabilities, including

- SQL injection
- revealing hidden folders , exposure sensitive data 
- the ability to recycle signups as other users
- reflected XSS
- Business Logic 
- Password leak
- Information disclosure in error
 These high-risk vulnerabilities should be promptly addressed to mitigate potential exploits.
 take control over the administrator account, delete users, get free items and make Juice Shop debit money to a bank account controlled by the attacker which would lead to financial impact through the different vulnerabilities found on the Juice Shop website. It would also be possible for malicious users to gain access to premium membership without paying which would lead to more financial losses to the Juice Shop Organization. Implications Based on the above testing activities the average risk level across the board is Critical. The website has a very small security posture and is currently vulnerable to Critical financial impact if compromised. The confidentiality and integrity of the web application is low and could lead to fines through GDPR regulations and should be addressed as soon as possible.


Significant Vulnerability Summary: 

High-Risk Vulnerabilities:

• SQL Injection
• Business Logic

Medium-Risk Vulnerabilities:

• Cross-Site Scripting
• Password leak
• Broken access control 

Low-Risk Vulnerabilities:

• revealing hidden folders and exposure sensitive data
• information disclosure in error



