CYBERSECURITY ROADMAP: FROM ABSOLUTE BEGINNER TO EXPERT

TANZANIA COMPUTING OPEN SOURCE COMMUNITY (TCOSC)

Document Type: Structured Learning, Practical Training and Professional Development Roadmap
Audience: Absolute beginners, university and college students, self-taught learners, junior practitioners and aspiring cybersecurity specialists
Learning Model: Understand → Practise → Build → Investigate → Document → Specialise → Contribute → Mentor
Approach: Skills-first, project-based, evidence-driven and progressively independent
Version: 1.0

======================================================================
1. PURPOSE OF THIS ROADMAP
======================================================================

This roadmap provides a progressive route from having little or no computing knowledge to developing advanced, independent cybersecurity expertise.

It is not simply a list of topics. Every stage defines what to learn, which resources to use, what practical exercises to complete, which projects to build and what abilities to demonstrate before progressing.

Cybersecurity expertise requires more than completing courses, collecting certificates or learning commands. It requires understanding computing systems, identifying weaknesses, interpreting evidence, designing effective defences and solving unfamiliar problems.

The roadmap prioritises demonstrated ability over course completion. Resources are selected for their practical value, technical depth and accessibility. Many core resources are free, although access conditions can change.

======================================================================
2. HOW TO FOLLOW THE ROADMAP
======================================================================

Follow the stages in sequence initially. Later, choose a specialisation while maintaining a broad understanding of computing and security.

For every stage:

1. Study the foundational material.
2. Reproduce the examples yourself.
3. Complete practical exercises without immediately following a walkthrough.
4. Build the required project or investigation.
5. Record what you did, what happened, why it happened and how you verified the result.
6. Revisit concepts you cannot explain clearly.
7. Advance when you meet the stage's exit criteria.

The time ranges are estimates, not guarantees. Progress depends on prior experience, consistency, practice quality and the difficulty of the chosen specialisation. Becoming an expert normally requires years of sustained practice.

======================================================================
STAGE 0 — ORIENTATION AND PROFESSIONAL MINDSET
======================================================================

Recommended duration: 1–2 weeks

OBJECTIVE

Understand what cybersecurity professionals do, the different career directions available and the ethical responsibilities of working with computer systems.

LEARN

- The difference between information security, cybersecurity, privacy and safety.
- The roles of security engineers, penetration testers, application security engineers, SOC analysts, incident responders, digital forensic investigators and security researchers.
- The difference between vulnerabilities, threats, risks, exploits, controls and incidents.
- The difference between authorised security testing and unauthorised access.
- How to use documentation, technical notes, version control and reproducible experiments.

RESOURCES

1. NIST Cybersecurity Framework:
   https://www.nist.gov/cyberframework

2. NIST NICE Cybersecurity Workforce Framework:
   https://www.nist.gov/itl/applied-cybersecurity/nice

3. OWASP:
   https://owasp.org/

PRACTICAL WORK

- Create a learning journal in Markdown.
- Record your current skills, goals and knowledge gaps.
- Choose a computer you own or have permission to administer for practice.
- Create a GitHub repository for learning notes and projects.
- Identify two or three cybersecurity specialisations that interest you.

DELIVERABLE

A personal learning plan containing your goals, available equipment, weekly study schedule and rules for safe practice.

EXIT CRITERIA

You can explain what cybersecurity professionals protect, the major types of security work and why permission is required before testing a system.

======================================================================
STAGE 1 — COMPUTER AND OPERATING SYSTEM FUNDAMENTALS
======================================================================

Recommended duration: 4–8 weeks

OBJECTIVE

Understand the computer as a working system before attempting to secure or test it.

LEARN

- CPU, memory, storage, processes and files.
- Binary, hexadecimal, character encoding and data representation.
- Applications, operating systems, services and system calls at an introductory level.
- Users, groups, permissions and administrative privileges.
- Filesystems, environment variables, processes and logs.
- Installing software, troubleshooting failures and reading system documentation.
- The difference between virtual machines, containers and physical computers.

RESOURCES IN LEARNING ORDER

1. Harvard CS50x — Introduction to Computer Science:
   https://cs50.harvard.edu/x/

2. Linux Journey:
   https://linuxjourney.com/

3. The Linux Command Line — free book:
   https://linuxcommand.org/tlcl.php

4. OverTheWire Bandit:
   https://overthewire.org/wargames/bandit/

5. Microsoft Learn:
   https://learn.microsoft.com/en-us/training/

PRACTICAL EXERCISES

- Install a Linux virtual machine.
- Navigate the filesystem using the terminal.
- Create users, groups, directories and files.
- Change and inspect permissions.
- Inspect running processes and services.
- Find and interpret system logs.
- Write simple shell scripts for file organisation and system information.
- Practise basic Windows administration and PowerShell if you have access to Windows.

PROJECT

Create a documented system-administration lab containing a Linux virtual machine, a user-permission exercise, a service-management exercise and a troubleshooting report.

EXIT CRITERIA

You can navigate the command line, explain basic permissions, inspect processes and services, locate relevant logs and troubleshoot common operating-system problems without relying entirely on tutorials.

======================================================================
STAGE 2 — NETWORKING AND INTERNET PROTOCOLS
======================================================================

Recommended duration: 6–10 weeks

OBJECTIVE

Understand how devices communicate, how internet services work and where network security controls operate.

Networking is a core prerequisite for penetration testing, incident response, cloud security, digital forensics and security engineering.

LEARN IN SEQUENCE

1. IP addresses, subnet masks, CIDR and routing.
2. Ethernet, MAC addresses, ARP and switching.
3. TCP and UDP, ports, connections and sockets.
4. DNS, DHCP, NAT and network address assignment.
5. HTTP, HTTPS, TLS and certificates.
6. Firewalls, VPNs, proxies and network segmentation.
7. Packet captures, connection failures and network troubleshooting.
8. IPv4 and IPv6 fundamentals.

RESOURCES IN LEARNING ORDER

1. Cisco Skills for All:
   https://skillsforall.com/

2. Practical Networking:
   https://www.practicalnetworking.net/

3. Cloudflare Learning Center:
   https://www.cloudflare.com/learning/

4. Wireshark Documentation:
   https://www.wireshark.org/docs/

5. RFC Editor — protocol specifications:
   https://www.rfc-editor.org/

PRACTICAL EXERCISES

- Build a small network in a simulator or virtual lab.
- Calculate subnets and identify network boundaries.
- Capture traffic and distinguish DNS, TCP, TLS and HTTP activity.
- Investigate failed connections using routing, DNS and socket tools.
- Explain what happens from entering a website address in a browser to receiving the page.
- Identify which information is visible in encrypted and unencrypted traffic.

PROJECT

Produce a network-lab report containing a topology diagram, IP addressing plan, packet captures, connectivity tests and troubleshooting findings.

EXIT CRITERIA

You can explain a connection from the application layer down to network transport, interpret basic packet captures and troubleshoot common DNS, routing, port and connection problems.

======================================================================
STAGE 3 — PROGRAMMING, AUTOMATION AND DEVELOPER TOOLS
======================================================================

Recommended duration: 8–12 weeks

OBJECTIVE

Learn enough programming to automate work, understand application behaviour and eventually investigate or build security tools.

You do not need to master every programming language. You do need to understand code rather than blindly execute tools created by other people.

LEARN IN SEQUENCE

1. Variables, data types, conditions, loops and functions.
2. Lists, dictionaries, sets, strings and file operations.
3. Exceptions, debugging, testing and code organisation.
4. Command-line arguments and environment variables.
5. JSON, CSV, regular expressions and log parsing.
6. HTTP requests and APIs.
7. Basic SQL and database interaction.
8. Git, branches, commits, diffs and code reviews.
9. Unit tests, dependency management and secure handling of secrets.

RESOURCES IN LEARNING ORDER

1. Python Tutorial:
   https://docs.python.org/3/tutorial/

2. Automate the Boring Stuff with Python:
   https://automatetheboringstuff.com/

3. Git Book:
   https://git-scm.com/book/en/v2

4. MDN JavaScript Guide:
   https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide

5. SQLBolt:
   https://sqlbolt.com/

PRACTICAL EXERCISES

- Write a script that parses a log file and counts events.
- Write a script that validates a list of URLs and records errors.
- Query a public API and process the returned JSON.
- Write tests for normal, invalid and unexpected input.
- Use Git to track changes and document why each change was made.
- Build a small application with input validation, error handling and useful logs.

PROJECT

Build a log-analysis utility that accepts a file, extracts defined fields, groups events, identifies selected patterns and exports a report. Document limitations and test cases.

EXIT CRITERIA

You can write, debug and explain a small program independently, read unfamiliar code, use Git and tests, and distinguish genuine program results from assumptions or fabricated output.

======================================================================
STAGE 4 — WEB TECHNOLOGIES, DATABASES AND APPLICATION ARCHITECTURE
======================================================================

Recommended duration: 6–10 weeks

OBJECTIVE

Understand the technologies that cybersecurity practitioners commonly investigate and secure.

LEARN IN SEQUENCE

1. HTML, CSS and JavaScript.
2. Browser behaviour, the DOM and client-side execution.
3. HTTP requests and responses, headers, methods, status codes and cookies.
4. URLs, query parameters, forms and content types.
5. Authentication, sessions and authorisation.
6. Server-side application logic and APIs.
7. Relational databases, SQL queries and database permissions.
8. Application configuration, dependencies and deployment.
9. Reverse proxies, web servers and application logs.
10. How frontend, backend, database and infrastructure components interact.

RESOURCES IN LEARNING ORDER

1. MDN Web Development:
   https://developer.mozilla.org/en-US/docs/Learn_web_development

2. MDN HTTP Overview:
   https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview

3. PostgreSQL Documentation:
   https://www.postgresql.org/docs/

4. The Missing Semester of Your CS Education:
   https://missing.csail.mit.edu/

PRACTICAL EXERCISES

- Build a small website with a form and a backend.
- Create an API endpoint and test its requests and responses.
- Use browser developer tools to inspect requests, cookies and page behaviour.
- Add a database and implement appropriate validation.
- Create user roles and verify that each role can access only permitted functions.
- Review application logs when requests fail.

PROJECT

Build a small web application with authentication, role-based access, a database and documented API endpoints. Include a diagram showing how the browser, server, database and infrastructure communicate.

EXIT CRITERIA

You can trace a user action through the browser, HTTP request, server logic and database, and explain where authentication, authorisation, validation and logging should occur.

======================================================================
STAGE 5 — SECURITY FUNDAMENTALS AND THREAT MODELLING
======================================================================

Recommended duration: 4–6 weeks

OBJECTIVE

Learn to reason about security before relying on scanning tools or exploit techniques.

LEARN

- Confidentiality, integrity and availability.
- Authentication versus authorisation.
- Least privilege, defence in depth and secure defaults.
- Assets, trust boundaries, attack surfaces and threat actors.
- Vulnerabilities, exploitability, likelihood, impact and risk.
- Security controls, monitoring and incident handling.
- Threat modelling and security requirements.
- Security testing limitations and false positives.
- Basic security policies and risk communication.

RESOURCES IN LEARNING ORDER

1. NIST Cybersecurity Framework:
   https://www.nist.gov/cyberframework

2. OWASP Top 10:
   https://owasp.org/www-project-top-ten/

3. MITRE ATT&CK:
   https://attack.mitre.org/

4. OWASP Threat Modeling:
   https://owasp.org/www-community/Threat_Modeling

5. CISA Secure by Design:
   https://www.cisa.gov/securebydesign

PRACTICAL EXERCISES

- Threat-model the web application built in Stage 4.
- Identify assets, trust boundaries and possible abuse cases.
- Map proposed controls to the risks they address.
- Assess sample findings and explain severity using evidence and context.
- Distinguish an actual vulnerability from a theoretical concern or scanner warning.

PROJECT

Create a threat model with a system diagram, assets, trust boundaries, threat scenarios, risk ratings, mitigations and residual risks.

EXIT CRITERIA

You can explain why a weakness matters, describe realistic attack conditions and propose controls that address the underlying cause rather than simply naming a tool or vulnerability.

======================================================================
STAGE 6 — CRYPTOGRAPHY, IDENTITY AND ACCESS CONTROL
======================================================================

Recommended duration: 4–8 weeks

OBJECTIVE

Understand the security mechanisms that protect identities, communications, stored data and system access.

LEARN

- Hashing versus encryption.
- Symmetric and public-key cryptography.
- Digital signatures, certificates and trust chains.
- TLS and secure communication.
- Password storage, salts and password verification.
- Multi-factor authentication and session management.
- Public-key authentication and SSH keys.
- Access-control models and privilege boundaries.
- Key storage, rotation, revocation and secret management.
- Common cryptographic design and implementation mistakes.

RESOURCES IN LEARNING ORDER

1. Stanford Online — Cryptography I:
   https://crypto.stanford.edu/~dabo/courses/OnlineCrypto/

2. web.dev:
   https://web.dev/learn/

3. OWASP Authentication Cheat Sheet:
   https://cheatsheetseries.owasp.org/cheatsheets/Authentication_Cheat_Sheet.html

4. OWASP Password Storage Cheat Sheet:
   https://cheatsheetseries.owasp.org/cheatsheets/Password_Storage_Cheat_Sheet.html

5. OpenSSL Documentation:
   https://docs.openssl.org/

PRACTICAL EXERCISES

- Inspect a TLS certificate chain.
- Generate and use an SSH key pair.
- Demonstrate why hashing and encryption solve different problems.
- Implement password verification using a well-maintained password-hashing library.
- Review an application's authentication and session-management design.
- Identify insecure secret storage in a deliberately vulnerable training application.

PROJECT

Write a security review of an authentication system, including password handling, session management, account recovery, authorisation and secret storage.

EXIT CRITERIA

You can explain what a cryptographic mechanism guarantees, what it does not guarantee and how poor implementation can undermine it.

======================================================================
STAGE 7 — BUILD A REPEATABLE SECURITY LAB
======================================================================

Recommended duration: 2–4 weeks initially; improve the lab throughout the roadmap.

OBJECTIVE

Create a controlled environment where you can safely investigate systems, reproduce findings and develop technical confidence.

RESOURCES

1. VirtualBox Documentation:
   https://www.virtualbox.org/wiki/Documentation

2. Parrot Security:
   https://www.parrotsec.org/

3. Ubuntu Documentation:
   https://documentation.ubuntu.com/

4. OWASP Juice Shop:
   https://owasp.org/www-project-juice-shop/

5. Docker Documentation:
   https://docs.docker.com/

PRACTICAL WORK

- Create separate virtual machines for a target system and a testing system.
- Use isolated or host-only networking where appropriate.
- Take snapshots before experiments and document recovery procedures.
- Store sample logs and packet captures for later analysis.
- Deploy a deliberately vulnerable application locally.
- Document the lab's network layout and boundaries.
- Practise backing up, restoring and rebuilding the environment.

PROJECT

Publish a lab guide containing setup steps, network configuration, safety boundaries, software versions, test cases and cleanup instructions.

EXIT CRITERIA

You can rebuild your lab, reproduce an experiment and explain how the lab is isolated from systems you do not have permission to test.

======================================================================
STAGE 8 — LINUX, WINDOWS AND NETWORK SECURITY
======================================================================

Recommended duration: 6–10 weeks

OBJECTIVE

Move from basic system administration to understanding how systems are hardened, monitored and investigated.

LEARN

- Linux users, permissions, services, scheduled tasks and system logs.
- Windows accounts, services, PowerShell, event logs and security controls.
- Processes, persistence mechanisms and privilege boundaries.
- Host firewalls, network filtering and segmentation.
- SSH, remote administration and secure configuration.
- Endpoint protection, audit policies and least privilege.
- Common misconfigurations and methods for verifying remediation.
- Windows domain and Active Directory fundamentals.

RESOURCES IN LEARNING ORDER

1. Ubuntu Server Security Documentation:
   https://documentation.ubuntu.com/server/how-to/security/

2. Microsoft Learn — Windows Security:
   https://learn.microsoft.com/en-us/windows/security/

3. Microsoft Learn — PowerShell:
   https://learn.microsoft.com/en-us/powershell/

4. CIS Benchmarks:
   https://www.cisecurity.org/cis-benchmarks

5. Microsoft Sysinternals:
   https://learn.microsoft.com/en-us/sysinternals/

6. OverTheWire Bandit:
   https://overthewire.org/wargames/bandit/

PRACTICAL EXERCISES

- Configure and review Linux file permissions.
- Audit enabled services and unnecessary network exposure.
- Investigate Linux authentication logs and Windows event logs.
- Configure firewall rules and verify their effects.
- Compare a default configuration with a hardened configuration.
- Create a least-privilege account and test its actual permissions.
- Practise identifying suspicious processes and unexpected configuration changes.

PROJECT

Produce a system-hardening report containing the initial configuration, identified weaknesses, remediation steps and evidence that the changes worked.

EXIT CRITERIA

You can administer basic Linux and Windows systems, investigate relevant logs, recognise common misconfigurations and verify that security controls operate as intended.

======================================================================
STAGE 9 — WEB APPLICATION SECURITY AND API TESTING
======================================================================

Recommended duration: 8–16 weeks

OBJECTIVE

Develop a rigorous understanding of web vulnerabilities through structured study, controlled testing and remediation.

LEARN IN SEQUENCE

1. HTTP request and response manipulation.
2. Authentication and session weaknesses.
3. Broken access control and insecure direct object references.
4. SQL injection and other injection vulnerabilities.
5. Cross-site scripting (XSS).
6. Cross-site request forgery (CSRF).
7. Path traversal and file-handling weaknesses.
8. Server-side request forgery (SSRF).
9. Security misconfiguration and insecure deployment.
10. API authorisation, rate limiting and input validation.
11. Business-logic flaws.
12. Secure remediation and regression testing.

RESOURCES IN LEARNING ORDER

1. PortSwigger Web Security Academy:
   https://portswigger.net/web-security

   Begin with introductory material, then complete Apprentice labs before progressing to Practitioner and Expert-level challenges where available.

2. OWASP Web Security Testing Guide:
   https://owasp.org/www-project-web-security-testing-guide/

3. OWASP Application Security Verification Standard:
   https://owasp.org/www-project-application-security-verification-standard/

4. OWASP API Security Project:
   https://owasp.org/www-project-api-security/

5. OWASP Juice Shop:
   https://owasp.org/www-project-juice-shop/

PRACTICAL EXERCISES

For each vulnerability class:

- Explain the underlying cause.
- Identify the conditions required for exploitation.
- Complete authorised training labs.
- Record the request, response and relevant evidence.
- Explain the impact without exaggerating it.
- Implement or describe an appropriate fix.
- Repeat the test to confirm whether the fix works.
- Consider whether the fix introduces regressions elsewhere.

PROJECT

Conduct an end-to-end security assessment of your own deliberately vulnerable or purpose-built web application. Include scope, methodology, findings, reproducible evidence, severity rationale, remediation and retesting.

EXIT CRITERIA

You can investigate common web vulnerabilities, distinguish confirmed findings from false positives, explain root causes and verify fixes. You should be able to solve some unfamiliar labs without relying on walkthroughs.

======================================================================
STAGE 10 — VULNERABILITY ASSESSMENT AND PENETRATION TESTING
======================================================================

Recommended duration: 8–16 weeks

OBJECTIVE

Learn how to plan and conduct authorised security assessments rather than merely operate scanning tools.

LEARN

- Defining scope, permissions, constraints and rules of engagement.
- Asset discovery and attack-surface mapping.
- Service identification and version verification.
- Vulnerability research and validation.
- Manual testing versus automated scanning.
- Exploit preconditions, impact and limitations.
- Privilege boundaries and controlled post-exploitation analysis.
- Evidence collection, reproducibility and risk-based prioritisation.
- False positives, false negatives and scanner limitations.
- Reporting, remediation advice and retesting.

RESOURCES IN LEARNING ORDER

1. Nmap Reference Guide:
   https://nmap.org/book/man.html

2. Nmap Documentation:
   https://nmap.org/docs.html

3. Metasploit Documentation:
   https://docs.metasploit.com/

4. Hack The Box:
   https://www.hackthebox.com/

5. picoCTF:
   https://picoctf.org/

6. OWASP Web Security Testing Guide:
   https://owasp.org/www-project-web-security-testing-guide/

PRACTICAL EXERCISES

- Assess a deliberately vulnerable virtual machine.
- Map its exposed services and explain why each one matters.
- Validate selected findings manually in the authorised lab.
- Compare automated scan results with verified evidence.
- Reproduce a finding after restoring the lab to its original state.
- Produce a professional report that a developer or system administrator can act on.

PROJECT

Complete a simulated penetration-test engagement against an isolated target. Deliver a scope statement, asset inventory, methodology, findings, evidence, executive summary, technical remediation plan and retest results.

EXIT CRITERIA

You can plan an authorised assessment, identify and validate weaknesses, understand the limits of your tools, maintain reproducible evidence and communicate technical risk professionally.

PROGRESSION RULE

Do not move directly into advanced exploitation simply because you have learned tool commands. You must understand the protocols, systems and vulnerabilities behind those commands.

======================================================================
STAGE 11 — SECURITY OPERATIONS, DETECTION AND THREAT HUNTING
======================================================================

Recommended duration: 8–12 weeks

OBJECTIVE

Learn how defenders detect, investigate and respond to suspicious activity in real environments.

LEARN IN SEQUENCE

1. Log sources and event normalisation.
2. Windows and Linux security telemetry.
3. Network traffic analysis.
4. Indicators of compromise and behavioural indicators.
5. SIEM searches, correlation and alert triage.
6. Detection engineering and false-positive reduction.
7. Threat intelligence and adversary behaviour.
8. MITRE ATT&CK mapping.
9. Endpoint detection and response concepts.
10. Incident escalation and evidence preservation.

RESOURCES IN LEARNING ORDER

1. Microsoft Learn — Security Training:
   https://learn.microsoft.com/en-us/training/browse/?products=security

2. MITRE ATT&CK:
   https://attack.mitre.org/

3. CyberDefenders:
   https://cyberdefenders.org/

4. Blue Team Labs Online:
   https://blueteamlabs.online/

5. Splunk Education:
   https://www.splunk.com/en_us/training.html

6. Sigma:
   https://sigmahq.io/

PRACTICAL EXERCISES

- Investigate a suspicious authentication pattern in sample logs.
- Analyse a packet capture and correlate it with host events.
- Write a detection rule for a clearly defined behaviour.
- Test the rule against benign and suspicious examples.
- Document the rule's assumptions, blind spots and false positives.
- Map observed behaviour to ATT&CK without treating a mapping as proof of an attack.

PROJECT

Build a small security-monitoring lab. Collect system logs, create at least three documented detections, test them with controlled activity and write an investigation report for each simulated alert.

EXIT CRITERIA

You can investigate an alert using multiple evidence sources, explain your conclusions, document uncertainty and propose improvements to detection coverage.

======================================================================
STAGE 12 — INCIDENT RESPONSE AND DIGITAL FORENSICS
======================================================================

Recommended duration: 8–12 weeks

OBJECTIVE

Learn how to respond to security incidents methodically, preserve evidence and reconstruct events from available data.

LEARN

- Incident preparation and response procedures.
- Triage, containment, eradication and recovery.
- Evidence integrity and chain of custody.
- File metadata, hashes and timelines.
- Windows and Linux artefacts.
- Memory, disk and network forensics fundamentals.
- Browser, authentication and process artefacts.
- Phishing investigation and suspicious-file triage.
- Reporting confidence, uncertainty and alternative explanations.

RESOURCES IN LEARNING ORDER

1. NIST Computer Security Incident Handling Guide:
   https://csrc.nist.gov/pubs/sp/800/61/r2/final

2. NIST Computer Forensics Tool Testing:
   https://www.nist.gov/itl/ssd/software-quality-group/computer-forensics-tool-testing-cftt

3. Autopsy:
   https://www.autopsy.com/

4. Volatility Foundation:
   https://volatilityfoundation.org/

5. CyberDefenders:
   https://cyberdefenders.org/

6. The DFIR Report:
   https://thedfirreport.com/

PRACTICAL EXERCISES

- Investigate a supplied forensic image or training dataset.
- Calculate hashes and preserve original evidence.
- Build a timeline from logs and artefacts.
- Investigate a simulated phishing incident.
- Correlate host, network and authentication events.
- Distinguish verified observations from hypotheses.
- Write a report that another investigator can reproduce.

PROJECT

Complete an incident-investigation case file containing the incident timeline, evidence register, analysis methods, findings, limitations, containment recommendations and lessons learned.

EXIT CRITERIA

You can preserve evidence, investigate a bounded incident, construct a defensible timeline and communicate what is known, what remains uncertain and what should happen next.

======================================================================
STAGE 13 — SECURE SOFTWARE, CLOUD AND INFRASTRUCTURE ENGINEERING
======================================================================

Recommended duration: 8–16 weeks

OBJECTIVE

Progress from identifying security weaknesses to designing, building and maintaining systems that resist them.

LEARN

- Secure design and threat modelling.
- Input validation, output encoding and safe data handling.
- Authentication, authorisation and session security.
- Dependency management and software supply-chain risks.
- Secrets management and secure configuration.
- Code review, security testing and continuous integration.
- Container security and infrastructure as code.
- Cloud identity, network controls, logging and storage permissions.
- Backup, recovery and resilience.
- Security monitoring and vulnerability remediation throughout a system's lifecycle.

RESOURCES IN LEARNING ORDER

1. OWASP Software Assurance Maturity Model:
   https://owaspsamm.org/

2. OWASP Application Security Verification Standard:
   https://owasp.org/www-project-application-security-verification-standard/

3. NIST Secure Software Development Framework:
   https://csrc.nist.gov/projects/ssdf

4. Docker Security:
   https://docs.docker.com/engine/security/

5. AWS Security Documentation:
   https://docs.aws.amazon.com/security/

6. Microsoft Azure Security:
   https://learn.microsoft.com/en-us/azure/security/

7. Google Cloud Security:
   https://cloud.google.com/security

8. GitHub Security Documentation:
   https://docs.github.com/en/code-security

PRACTICAL EXERCISES

- Review your Stage 4 application against an application-security checklist.
- Correct a vulnerability and add a regression test.
- Remove hard-coded secrets and implement safer configuration.
- Scan dependencies and evaluate the significance of the results.
- Deploy an application with restricted permissions and useful audit logs.
- Test backup restoration and document recovery limitations.
- Build a basic security check into a software delivery workflow.

PROJECT

Publish a secure application deployment with an architecture diagram, threat model, security tests, dependency review, logging plan, deployment instructions and documented remediation history.

EXIT CRITERIA

You can integrate security into development and deployment, justify controls, test their effectiveness and maintain a system beyond its initial release.

======================================================================
STAGE 14 — ADVANCED SPECIALISATION
======================================================================

Recommended duration: 6–18 months initially, followed by continuing development.

OBJECTIVE

Develop deep competence in one or two disciplines while retaining enough breadth to collaborate with specialists in other areas.

Do not attempt to master every specialisation simultaneously. Select one primary path based on the work you want to perform and use the others to strengthen your overall understanding.

----------------------------------------------------------------------
PATH A — WEB APPLICATION SECURITY AND APPLICATION SECURITY ENGINEERING
----------------------------------------------------------------------

BEST SUITED TO

Learners interested in application vulnerabilities, secure coding, API security and helping developers build safer systems.

STUDY SEQUENCE

1. Complete relevant learning material in PortSwigger Web Security Academy:
   https://portswigger.net/web-security

2. Work through the OWASP Web Security Testing Guide:
   https://owasp.org/www-project-web-security-testing-guide/

3. Study the OWASP ASVS:
   https://owasp.org/www-project-application-security-verification-standard/

4. Study the OWASP API Security Project:
   https://owasp.org/www-project-api-security/

5. Learn secure code review, dependency analysis, authentication design, access-control testing and security testing in CI/CD.

6. Read Google Security Blog:
   https://security.googleblog.com/

7. Study Google Project Zero:
   https://googleprojectzero.blogspot.com/

ADVANCED PRACTICAL WORK

- Assess complex authentication and authorisation workflows in authorised environments.
- Identify business-logic weaknesses that automated scanners may miss.
- Review application code and trace a vulnerability from its root cause to its impact.
- Build a security regression test for each confirmed issue.
- Write a technical advisory with reproducible evidence and a practical fix.

ADVANCED MILESTONE

You can identify unfamiliar application weaknesses, explain their root causes, design fixes and independently verify that the fixes work.

----------------------------------------------------------------------
PATH B — PENETRATION TESTING AND OFFENSIVE SECURITY
----------------------------------------------------------------------

BEST SUITED TO

Learners interested in authorised adversary simulation, security assessments and attack-path analysis.

STUDY SEQUENCE

1. Strengthen networking, Linux, Windows and web fundamentals.
2. Complete structured exercises on TryHackMe:
   https://tryhackme.com/
3. Practise independent challenges on Hack The Box:
   https://www.hackthebox.com/
4. Study Nmap:
   https://nmap.org/book/man.html
5. Study Metasploit:
   https://docs.metasploit.com/
6. Learn Active Directory security and identity infrastructure in a dedicated lab.
7. Study MITRE ATT&CK:
   https://attack.mitre.org/
8. Practise planning, scoping, evidence collection and professional reporting.

ADVANCED PRACTICAL WORK

- Complete an assessment from scope definition through final reporting.
- Reproduce complex findings without depending on walkthroughs.
- Explain the prerequisites and limitations of each demonstrated weakness.
- Demonstrate remediation and retest results.
- Write reports suitable for both technical engineers and management.

ADVANCED MILESTONE

You can conduct a scoped assessment independently, make defensible technical judgments and communicate findings that help the system owner reduce risk.

----------------------------------------------------------------------
PATH C — SECURITY OPERATIONS AND DETECTION ENGINEERING
----------------------------------------------------------------------

BEST SUITED TO

Learners interested in monitoring, threat detection, investigations and improving defensive capability.

STUDY SEQUENCE

1. Strengthen Windows, Linux, networking and log analysis.
2. Practise with CyberDefenders:
   https://cyberdefenders.org/
3. Practise with Blue Team Labs Online:
   https://blueteamlabs.online/
4. Study MITRE ATT&CK:
   https://attack.mitre.org/
5. Learn a SIEM's search language and data model.
6. Study Sigma:
   https://sigmahq.io/
7. Read real incident reports and compare the available evidence with the detections that could have identified the activity.

ADVANCED PRACTICAL WORK

- Create detections with measurable objectives.
- Test them against benign and suspicious activity.
- Reduce false positives without losing important coverage.
- Investigate incidents using endpoint, network and identity evidence.
- Document detection gaps and recommend improvements.

ADVANCED MILESTONE

You can design, test, tune and maintain detections, and lead a defensible investigation rather than simply follow an alert-handling checklist.

----------------------------------------------------------------------
PATH D — DIGITAL FORENSICS AND INCIDENT RESPONSE
----------------------------------------------------------------------

BEST SUITED TO

Learners interested in reconstructing incidents, analysing digital evidence and supporting investigations.

STUDY SEQUENCE

1. Master operating-system artefacts, filesystems, networking and logging.
2. Practise using Autopsy:
   https://www.autopsy.com/
3. Study Volatility:
   https://volatilityfoundation.org/
4. Read The DFIR Report:
   https://thedfirreport.com/
5. Work through authorised forensic datasets and CyberDefenders challenges:
   https://cyberdefenders.org/
6. Learn evidence integrity, timeline construction and incident reporting.
7. Study file formats, memory artefacts and advanced forensic techniques relevant to your chosen work.

ADVANCED PRACTICAL WORK

- Investigate an unfamiliar dataset without a walkthrough.
- Build a timeline from multiple evidence sources.
- Validate important findings independently.
- Document alternative explanations and evidence limitations.
- Produce a case report that another investigator can reproduce.

ADVANCED MILESTONE

You can investigate complex incidents, preserve evidence correctly and support conclusions with verifiable artefacts.

----------------------------------------------------------------------
PATH E — MALWARE ANALYSIS AND REVERSE ENGINEERING
----------------------------------------------------------------------

BEST SUITED TO

Learners interested in understanding suspicious programs and how they behave.

STUDY SEQUENCE

1. Learn C fundamentals, assembly basics, processes, memory and executable formats.
2. Understand operating-system internals and debugging.
3. Study static analysis, dynamic analysis and behavioural observation.
4. Learn the purpose and limits of disassemblers, debuggers and sandbox environments.
5. Use isolated, disposable labs and authorised malware-analysis datasets.
6. Study Ghidra:
   https://ghidra-sre.org/
7. Study MITRE ATT&CK:
   https://attack.mitre.org/

ADVANCED PRACTICAL WORK

- Analyse benign test programs and controlled samples before moving to more complex datasets.
- Identify program behaviour and important code paths.
- Explain suspicious network or filesystem activity.
- Document indicators and the limits of your analysis.
- Produce a behavioural report with reproducible evidence.

ADVANCED MILESTONE

You can analyse unfamiliar binaries methodically, explain relevant behaviour and distinguish confirmed observations from assumptions.

----------------------------------------------------------------------
PATH F — CLOUD AND INFRASTRUCTURE SECURITY
----------------------------------------------------------------------

BEST SUITED TO

Learners interested in securing cloud workloads, identities, networks and production infrastructure.

STUDY SEQUENCE

1. Strengthen networking, Linux, identity and automation.
2. Choose one cloud provider initially:
   AWS: https://docs.aws.amazon.com/security/
   Azure: https://learn.microsoft.com/en-us/azure/security/
   Google Cloud: https://cloud.google.com/security

3. Study identity and access management, network controls, logging, encryption and storage permissions.
4. Learn containers and infrastructure as code.
5. Study secure deployment, monitoring, secrets management and recovery.
6. Practise configuration review in accounts and environments you own or are explicitly authorised to assess.

ADVANCED PRACTICAL WORK

- Design a cloud architecture with restricted permissions and clear trust boundaries.
- Detect and correct insecure configurations.
- Create repeatable infrastructure deployments.
- Verify logging, alerting and backup recovery.
- Document the risks and trade-offs of the architecture.

ADVANCED MILESTONE

You can design, deploy and review a secure infrastructure environment, explain its trust relationships and verify that its controls work.

----------------------------------------------------------------------
PATH G — SECURITY ENGINEERING AND PRODUCT SECURITY
----------------------------------------------------------------------

BEST SUITED TO

Learners who want to build security mechanisms, tools and reliable security systems.

STUDY SEQUENCE

1. Deepen programming, operating systems and networking.
2. Study secure architecture and threat modelling.
3. Learn code review, test design, CI/CD and dependency security.
4. Study security protocols, identity systems and endpoint controls.
5. Explore the NIST Secure Software Development Framework:
   https://csrc.nist.gov/projects/ssdf

6. Explore OWASP SAMM:
   https://owaspsamm.org/

7. Build and maintain a real project with security requirements, tests, logging and release practices.

ADVANCED PRACTICAL WORK

- Build a security feature with explicit requirements and tests.
- Design a small detection or validation tool.
- Review its failure modes, performance and security implications.
- Publish technical documentation and test results.
- Maintain the tool as dependencies and requirements change.

ADVANCED MILESTONE

You can design and maintain security functionality, justify its engineering decisions and demonstrate its effectiveness through testing.

----------------------------------------------------------------------
PATH H — GOVERNANCE, RISK AND SECURITY ASSURANCE
----------------------------------------------------------------------

BEST SUITED TO

Learners interested in organisational risk, security policy, audits, compliance and security programme improvement.

STUDY SEQUENCE

1. Learn assets, threats, risk, controls and business impact.
2. Study the NIST Cybersecurity Framework:
   https://www.nist.gov/cyberframework

3. Explore CIS Controls:
   https://www.cisecurity.org/controls

4. Study ISO/IEC 27001 concepts:
   https://www.iso.org/isoiec-27001-information-security.html

5. Learn risk registers, control assessments, audit evidence and remediation tracking.
6. Connect governance decisions to actual technical evidence and operational outcomes.

ADVANCED PRACTICAL WORK

- Assess a hypothetical organisation's security risks.
- Build a risk register and prioritised treatment plan.
- Map controls to business requirements.
- Evaluate whether selected controls are actually operating.
- Write a concise, evidence-based management report.

ADVANCED MILESTONE

You can translate technical risks into clear business decisions and assess security controls based on evidence rather than paperwork alone.

======================================================================
STAGE 15 — SECURITY RESEARCH AND ORIGINAL CONTRIBUTION
======================================================================

Recommended duration: Ongoing. Begin small projects during earlier stages.

OBJECTIVE

Move beyond reproducing known techniques to investigating questions independently and contributing useful knowledge to the field.

LEARN

- How to formulate a research question.
- How to search technical literature and vendor documentation.
- How to reproduce a published result.
- How to separate observations from interpretations.
- How to measure results and report limitations.
- How to communicate a finding responsibly.
- How to maintain a technical project and respond to peer review.

RESOURCES

1. USENIX Security Symposium:
   https://www.usenix.org/conferences/byname/108

2. IEEE Security & Privacy:
   https://www.computer.org/csdl/magazine/sp

3. Google Project Zero:
   https://googleprojectzero.blogspot.com/

4. NIST Publications:
   https://csrc.nist.gov/publications

5. CVE Program:
   https://www.cve.org/

PRACTICAL WORK

- Reproduce a published security finding in a controlled environment.
- Write a clear technical explanation of the root cause.
- Build a small tool that addresses a real, well-defined problem.
- Compare approaches using reproducible tests.
- Publish a research note that states the methodology, evidence, limitations and conclusions.
- Contribute a documentation improvement, bug report, test case or code change to an open-source project.

PROJECT

Publish a reproducible technical investigation or useful open-source security tool, including its purpose, design, tests, limitations and maintenance plan.

EXIT CRITERIA

You can formulate a technical question, investigate it independently, produce evidence and communicate a result that other practitioners can evaluate and reproduce.

======================================================================
STAGE 16 — PROFESSIONAL-LEVEL PRACTICE AND EXPERTISE
======================================================================

Recommended duration: Several years of continuing practice.

OBJECTIVE

Develop the judgment, depth and independence expected of a highly capable cybersecurity practitioner.

There is no single course or certificate that makes someone an expert. Expertise develops through repeated work on difficult problems, feedback from experienced practitioners, responsible decisions and the ability to explain and defend technical conclusions.

WHAT TO DO AT THIS STAGE

1. Investigate unfamiliar problems without depending on a tutorial for every task.
2. Work with realistic constraints, including performance, cost, availability, privacy, usability and operational risk.
3. Study failures, incidents, failed controls, misleading findings and unsuccessful remediation.
4. Read primary technical material, including specifications, source code, research papers and advisories.
5. Build and maintain reliable systems and tools.
6. Seek rigorous review from experienced practitioners.
7. Teach what you understand and help beginners progress.
8. Stay current with relevant vulnerability advisories, technical research and defensive techniques.
9. Develop professional judgment: know when to test, when to stop, when evidence is insufficient and when to seek specialist help.
10. Contribute to open-source projects, publish useful research and share responsible technical knowledge.

ADVANCED EVIDENCE OF COMPETENCE

A mature practitioner should be able to demonstrate several of the following, appropriate to their specialisation:

- Solve unfamiliar technical problems without relying on step-by-step instructions.
- Explain underlying mechanisms rather than merely reproduce a tool's output.
- Design experiments that distinguish competing explanations.
- Produce reliable, maintainable technical work.
- Identify limitations and uncertainty in their own conclusions.
- Make technically and ethically defensible decisions.
- Review other practitioners' work constructively.
- Communicate complex findings clearly to different audiences.
- Demonstrate sustained contribution to real projects, investigations or research.

FINAL MILESTONE

You can independently identify meaningful problems, investigate them rigorously, produce defensible results, improve systems or understanding, and help other practitioners develop their skills.

This is a continuing professional standard, not a final certificate or a point at which learning ends.

======================================================================
3. THE PRACTICAL LEARNING ROUTINE
======================================================================

A roadmap only works when it becomes a consistent routine.

Use the following weekly schedule as a starting point.

STRUCTURED STUDY AND TECHNICAL READING: 3–5 hours
HANDS-ON LABS AND EXPERIMENTS: 4–6 hours
PROJECTS AND INDEPENDENT CHALLENGES: 2–4 hours
DOCUMENTATION, REVIEW AND REFLECTION: 1–2 hours

TOTAL: Approximately 10–17 hours per week.

These are planning suggestions, not mandatory minimums. Consistent practice is more valuable than following an unrealistic schedule for a few weeks and abandoning it.

THE LEARNING CYCLE

Study → Reproduce → Experiment → Break safely → Diagnose → Fix → Retest → Document

For every significant exercise, record:

- OBJECTIVE: What are you trying to understand?
- ENVIRONMENT: Which systems, versions and configurations are involved?
- METHOD: What steps did you perform?
- EVIDENCE: What did you actually observe?
- ANALYSIS: Why did the result occur?
- LIMITATIONS: What does the result not prove?
- REMEDIATION: How could a weakness be addressed?
- VERIFICATION: How did you confirm the outcome?
- NEXT STEP: What question should you investigate next?

This habit helps turn exercises into durable technical knowledge.

======================================================================
4. BUILD A PORTFOLIO THAT DEMONSTRATES REAL SKILL
======================================================================

Do not measure progress solely by the number of courses, badges or challenges completed. Maintain a portfolio that shows what you can actually do.

BEGINNER PORTFOLIO

- Linux administration notes and scripts.
- Networking diagrams and packet-analysis exercises.
- Basic Python utilities.
- A small web application.
- Documented security concepts with reproducible examples.

INTERMEDIATE PORTFOLIO

- A threat model for an application.
- A system-hardening report with verification evidence.
- A web application security assessment with fixes and retesting.
- A log-analysis utility with automated tests.
- A small security-monitoring lab with documented detections.
- A digital-forensics investigation using an authorised dataset.

ADVANCED PORTFOLIO

- An independently completed technical investigation.
- A security tool with tests, documentation and maintenance history.
- A detailed incident analysis based on verifiable evidence.
- A secure application or infrastructure deployment.
- A research reproduction or original technical analysis.
- Meaningful contributions to an established open-source project.

For every portfolio item, explain the problem, your approach, the evidence, the result and the limitations.

Never publish credentials, private data, exploitable details about systems without permission or confidential information from an employer or client.

======================================================================
5. HOW TO KNOW WHEN YOU ARE READY TO ADVANCE
======================================================================

At the end of every stage, ask yourself:

1. Can I explain the concept without copying a definition?
2. Can I perform the practical task without following every instruction?
3. Can I explain why the method works?
4. Can I diagnose a failure and use evidence to find its cause?
5. Can I recognise when a result is incomplete or misleading?
6. Can I document the work so another person can reproduce it?
7. Can I explain the security implications and appropriate mitigations?

If several answers are no, revisit the relevant material and practise again.

A learner who understands a smaller set of concepts deeply is generally better prepared for advanced work than someone who has superficially completed many unrelated topics.

======================================================================
6. HOW TCOSC LEARNERS SHOULD USE THIS ROADMAP
======================================================================

The Tanzania Computing Open Source Community (TCOSC) can use this roadmap as a shared foundation for learners across universities, colleges and independent learning groups.

RECOMMENDED COMMUNITY ACTIVITIES

- Publish study notes and resource corrections.
- Organise peer-led learning sessions around each stage.
- Build shared, legal training labs.
- Create beginner-friendly projects with progressively harder tasks.
- Review one another's code, documentation and technical reports.
- Maintain public portfolios and open-source contributions.
- Encourage experienced members to mentor beginners.
- Review the roadmap periodically as resources and technologies change.

Contributions should be practical, verifiable and useful to learners. Contributors should explain why a resource belongs at a particular stage and what skills a learner should gain from it.

OFFICIAL TCOSC GITHUB ORGANISATION

https://github.com/tanzania-computing-open-community

======================================================================
7. CORE RESOURCE DIRECTORY
======================================================================

FOUNDATIONS AND COMPUTING

Harvard CS50x:
https://cs50.harvard.edu/x/

Linux Journey:
https://linuxjourney.com/

The Linux Command Line:
https://linuxcommand.org/tlcl.php

OverTheWire Bandit:
https://overthewire.org/wargames/bandit/

Cisco Skills for All:
https://skillsforall.com/

PROGRAMMING AND WEB TECHNOLOGIES

Python Tutorial:
https://docs.python.org/3/tutorial/

Automate the Boring Stuff:
https://automatetheboringstuff.com/

Git Book:
https://git-scm.com/book/en/v2

MDN Web Development:
https://developer.mozilla.org/en-US/docs/Learn_web_development

SQLBolt:
https://sqlbolt.com/

SECURITY FOUNDATIONS AND STANDARDS

NIST Cybersecurity Framework:
https://www.nist.gov/cyberframework

NIST NICE:
https://www.nist.gov/itl/applied-cybersecurity/nice

OWASP:
https://owasp.org/

MITRE ATT&CK:
https://attack.mitre.org/

CIS Controls:
https://www.cisecurity.org/controls

HANDS-ON SECURITY PRACTICE

PortSwigger Web Security Academy:
https://portswigger.net/web-security

TryHackMe:
https://tryhackme.com/

Hack The Box:
https://www.hackthebox.com/

picoCTF:
https://picoctf.org/

OWASP Juice Shop:
https://owasp.org/www-project-juice-shop/

CyberDefenders:
https://cyberdefenders.org/

Blue Team Labs Online:
https://blueteamlabs.online/

RESEARCH AND PROFESSIONAL DEVELOPMENT

Google Project Zero:
https://googleprojectzero.blogspot.com/

The DFIR Report:
https://thedfirreport.com/

NIST Publications:
https://csrc.nist.gov/publications

CVE Program:
https://www.cve.org/

USENIX Security:
https://www.usenix.org/conferences/byname/108

======================================================================
8. FINAL PRINCIPLE
======================================================================

The destination is not the ability to name vulnerabilities or operate a collection of tools. It is the ability to understand systems, identify and investigate security problems, build effective solutions, verify results and contribute reliable knowledge.

Follow the roadmap in order, practise consistently, preserve evidence of your work and specialise progressively.

LEARN → PRACTISE → BUILD → INVESTIGATE → DOCUMENT → SPECIALISE → CONTRIBUTE → MENTOR

TANZANIA COMPUTING OPEN SOURCE COMMUNITY (TCOSC)

GitHub:
https://github.com/tanzania-computing-open-community
