# WEB-SECURIEY-REPORT
[README.md](https://github.com/user-attachments/files/18246219/README.md)
# OSWAP TOP 10

#### Chapter: 1- INTRODUCTION

Open Web Application Security Project , or OSWAP refers to the Top 10 as an ‘awareness document ’ and they recommend that all companies  incorporate the report into their processes in order to minimize and/or mitigate security risks. 

#### Chapter: 2- INJECTION

Injection attacks happen when untrusted data is sent to a code interpreter through a form input or some other data submission to a web application .
Injection attacks can be prevented by validating and/or sanitizing user-submitted data.(Validation means rejecting suspicious-looking data).

#### Chapter: 3- BROKEN AUTHENTICATION

Broken authentication is a vulnerability that can give attackers access to user accounts and even the ability to compromise an entire system using a admin account.
Two factor Authentication (2FA) is one the strategies to mitigate authentication vulnerabilities.



#### Chapter: 4- SENSITIVE DATA EXPOSURE 

If the web application don’t protect sensitive data such as username , password ,financial information etc . it may give the access to the attacker to manipulate or misuse the data .
In order to prevent: web application should try to avoid taking unnecessary sensitive information of a user and maintain the secrecy of the sensitive data.

#### Chapter: 5- XML External Entity 

XXE or (XML External Entity) is a vulnerability that often allows an attacker to interact with any backend or external systems that the application itself can access and can allow the attacker to read the file on that system. It can also cause Denial of Service (DoS) attack.

#### Chapter:6- BROKEN ACCESS CONTROL

Broken Access Control allows attackers to bypass authorization which allow them to view sensitive data or perform tasks as if they were a privileged user .

#### Chapter:7- SECURITY MISCONFIGURATION 

Security misconfiguration is the most common vulnerability on the list, and this is often the result of using default configurations or displaying excessively verbose errors.

#### Chapter:8- Cross-Site Scripting

Cross Site Scripting ,also known as XSS is a type of injection which allows an attacker to execute malicious scripts and have it execute on a victim’s machine.

#### Chapter:9- INSECURE DESERIALISATION

Insecure Deserialisation is a vulnerability which occur when untrusted data used to abuse the logic of an application. In other word, insecure deserialization is replacing data processed by an application with malicious code.

#### Chapter:10- COMPONENETS WITH KNOWN VULNERABILITIES

Components  with known vulnerabilities refers to software components that have security flaws or weaknesses that have been identified and publicly disclosed. These vulnerabilities can be the result of coding error, design flaws , or outdated libraries or framework. 
Attackers can exploit these vulnerabilities to gain unauthorized access to systems, disrupt operation and steal sensitive data.

#### Chapter:11- INSUFFICIENT LOGGING AND MONITORING

Insufficient logging and monitoring refers to a security vulnerability that occurs when a system is not correctly detected , logged or monitored successfully. Which can further lead to unauthorized access .

#### Chapter : 12- CONCLUSION 

The OSWAP Top 10 is a standard awareness document for developers and web application security .It represents a broad consensus about the most crucial security risks to web applications.




#### REFERENCE :
 - [OWASP TOP 10 ](https://tryhackme.com/r/room/owasptop10)
 - [OWASP top 10](https://www.cloudflare.com/learning/security/threats/owasp-top-10/ )
 - [OWASP  Testing Guide ](https://owasp.org/www-project-web-security-testing-guide/)



