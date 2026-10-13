# Writeups

**Tanzania Computing Open Source Community (TCOSC)**

A collection of practical cybersecurity walkthroughs, CTF solutions, technical investigations, and lessons learned through hands-on challenges.

## About This Section

Writeups document the process of investigating and solving cybersecurity challenges. They explain the techniques, tools, reasoning, and discoveries behind a solution so that other learners can understand the process and develop their own skills.

This section of TCOSC focuses on practical learning through Capture The Flag (CTF) competitions, cybersecurity training platforms, wargames, vulnerable machines, and authorised security laboratories.

Our goal is to build a community-driven knowledge base where learners can share experience, learn from one another, and develop practical cybersecurity skills.

We encourage original explanations that go beyond providing answers by explaining **what was done, why it worked, what was learned, and how the knowledge can be applied defensively**.

## Objectives

- Share practical cybersecurity knowledge gained through challenges and competitions.
- Help beginners understand techniques used in real security investigations.
- Document reproducible solutions and problem-solving approaches.
- Encourage independent learning and critical thinking.
- Explore different tools, techniques, and methodologies.
- Preserve useful technical knowledge for future learners.
- Promote collaboration, peer learning, and knowledge sharing.
- Connect theoretical security concepts with hands-on practice.

## Areas of Writeups

### 1. Linux and Wargames

Learn Linux fundamentals, command-line operations, file permissions, users and groups, SSH, shell scripting, and privilege boundaries through practical challenges.

### 2. Web Application Security

Explore HTTP, authentication, session management, access control, SQL injection, cross-site scripting (XSS), server-side request forgery (SSRF), API vulnerabilities, and other web security challenges.

### 3. Network Security

Document network discovery, TCP/IP, DNS, packet analysis, network protocols, service enumeration, and network-based challenges.

### 4. Digital Forensics

Investigate files, metadata, disk artefacts, memory captures, packet captures, event logs, and other digital evidence.

### 5. Reverse Engineering

Explore executable files, assembly, debugging, disassembly, program behaviour, and techniques for understanding compiled applications.

### 6. Binary Exploitation

Study memory corruption, buffer overflows, unsafe memory operations, binary protections, crash analysis, and controlled exploitation challenges.

### 7. Cryptography

Document challenges involving encoding, classical ciphers, encryption, hashing, key handling, cryptographic weaknesses, and mathematical problem-solving.

### 8. OSINT and Digital Intelligence

Explore public-source investigations, domain research, metadata analysis, information correlation, and digital intelligence challenges.

### 9. Windows and Active Directory

Investigate Windows internals, authentication, directory services, permissions, identity management, misconfigurations, and authorised enterprise security labs.

### 10. Malware Analysis

Document safe, controlled investigations of suspicious files, malware behaviour, file formats, static analysis, sandbox observations, and defensive detection.

### 11. Cloud and Container Security

Explore cloud identity, storage permissions, container security, infrastructure misconfigurations, and cloud-based security challenges.

### 12. Defensive Security and Threat Hunting

Document log analysis, security monitoring, incident response, detection engineering, threat hunting, and blue-team investigations.

### 13. Programming and Miscellaneous Challenges

Explore scripting, programming, steganography, data processing, encoding, automation, and other challenges that develop useful computing and security skills.

## Recommended CTF Platforms and Learning Resources

### Hack The Box

**Website:** https://www.hackthebox.com/

**Official Starting Point walkthroughs:** https://help.hackthebox.com/en/articles/6007919-introduction-to-starting-point

Hack The Box provides practical cybersecurity challenges involving penetration testing, Linux and Windows systems, web applications, networking, Active Directory, reverse engineering, and defensive security.

Its Starting Point pathway is a useful entry point for learners developing their foundational skills. More advanced challenges help develop deeper investigation and problem-solving abilities.

### TryHackMe

**Website:** https://tryhackme.com/

**Official help centre:** https://help.tryhackme.com/

TryHackMe offers guided rooms, structured learning paths, and practical security challenges for different experience levels.

Topics include Linux, networking, web security, Windows, Active Directory, privilege escalation, digital forensics, threat intelligence, and security operations.

### OverTheWire

**Website:** https://overthewire.org/wargames/

**Official rules:** https://overthewire.org/rules/

OverTheWire provides wargames that teach security concepts through hands-on terminal challenges.

Its games cover Linux commands, SSH, file permissions, programming, network services, and other foundational topics.

Bandit is a particularly useful starting point for learners who want to improve their Linux and command-line skills.

**Important:** Respect OverTheWire's rules, including its prohibition on publishing game credentials.

### CTFtime

**Website:** https://ctftime.org/

**Writeup archive:** https://ctftime.org/writeups

CTFtime lists CTF competitions, teams, events, and publicly available writeups from competitions around the world.

It is useful for studying how participants solve challenges in web security, cryptography, reverse engineering, binary exploitation, forensics, OSINT, and other categories.

### picoCTF

**Website:** https://picoctf.org/

**Practice platform:** https://play.picoctf.org/

picoCTF offers accessible cybersecurity challenges designed to help learners develop practical skills.

Its challenges cover general skills, cryptography, forensics, web exploitation, reverse engineering, and binary exploitation.

### Root-Me

**Website:** https://www.root-me.org/

**Challenges:** https://www.root-me.org/en/Challenges/

Root-Me provides a wide range of practical exercises covering web security, network protocols, programming, cryptography, reverse engineering, forensics, and system security.

It is useful for learners who want to explore multiple technical areas and practise solving independent challenges.

### VulnHub

**Website:** https://www.vulnhub.com/

VulnHub provides vulnerable virtual machines for hands-on security learning in controlled laboratory environments.

Learners can practise reconnaissance, service enumeration, web application testing, privilege escalation, and system investigation.

Use isolated virtual machines and ensure that testing remains within authorised environments.

### PortSwigger Web Security Academy

**Website:** https://portswigger.net/web-security

PortSwigger Web Security Academy offers free learning materials and interactive labs focused on web application security.

Topics include SQL injection, cross-site scripting, access control, authentication, SSRF, request smuggling, business logic vulnerabilities, and API security.

It is particularly useful for learners who want to understand web vulnerabilities through practical exercises.

### CyberDefenders

**Website:** https://cyberdefenders.org/

CyberDefenders provides blue-team challenges and practical exercises in digital forensics, incident response, threat hunting, malware analysis, and security operations.

Its challenges help learners practise investigating evidence, analysing logs, reconstructing events, and developing defensible conclusions.

### Blue Team Labs Online

**Website:** https://blueteamlabs.online/

Blue Team Labs Online provides defensive security exercises covering incident response, threat intelligence, digital forensics, log analysis, and security monitoring.

It is a useful resource for learners interested in defensive cybersecurity rather than penetration testing alone.

### Google Capture The Flag

**Website:** https://capturetheflag.withgoogle.com/

Google CTF features technical challenges involving cryptography, reverse engineering, web security, binary exploitation, and other cybersecurity topics.

Public competition materials can help learners study advanced techniques and understand how complex challenges are constructed.

### DEF CON Capture the Flag

**Website:** https://defcon.org/html/defcon-ctf.html

DEF CON CTF is associated with advanced security competitions and technically demanding challenges.

It is a useful reference for experienced learners interested in binary exploitation, reverse engineering, systems security, and complex vulnerability research.

### Hack This Site

**Website:** https://www.hackthissite.org/

Hack This Site provides security-related missions and exercises designed to help learners understand web technologies, programming, and security concepts.

Use the platform within its stated rules and authorised exercise environments.

## What Makes a Good Writeup?

A good writeup should help another person understand the investigation rather than simply reveal the final answer.

A useful writeup generally explains:

- **Challenge overview:** The platform, challenge name, category, and learning objectives.
- **Initial observations:** What was known at the beginning.
- **Tools used:** The tools, commands, and relevant configurations.
- **Investigation process:** The steps taken and the reasoning behind them.
- **Technical explanation:** Why the technique worked and what underlying concept it demonstrates.
- **Evidence:** Relevant output, screenshots, code snippets, or observations where permitted.
- **Alternative approaches:** Other methods considered or tested.
- **Lessons learned:** What the investigation taught the author.
- **Defensive relevance:** Where applicable, how the technique can be detected, prevented, or mitigated.
- **References:** Links to official documentation and other relevant sources.

Be accurate about what you actually tested. Do not fabricate command output, screenshots, flags, or successful results.

## Responsible Learning and Challenge Integrity

TCOSC encourages ethical, legal, and responsible cybersecurity practice.

Contributors should:

- Work within the platform's authorised challenge environment.
- Respect platform rules and competition restrictions.
- Avoid testing unrelated systems without permission.
- Never publish credentials or private challenge information.
- Avoid exposing personal data, secrets, or confidential material.
- Follow challenge-specific rules on publishing solutions.
- Credit original challenge authors and relevant references.
- Write original explanations rather than copying other authors' work.
- Use isolated environments when investigating potentially dangerous files or software.

Some platforms restrict public walkthroughs, challenge answers, or disclosure during active competitions. Always check the applicable rules before publishing a writeup.

## Who Can Contribute?

Writeups are welcome from:

- Beginners documenting their first successful challenges.
- Students practising computing and cybersecurity skills.
- CTF participants sharing their approaches.
- Developers investigating application behaviour and vulnerabilities.
- Security researchers documenting technical discoveries.
- Defensive security practitioners explaining investigations.
- Experienced contributors mentoring other learners.

You do not need to solve an advanced challenge to contribute something valuable. A clear explanation of a basic Linux command, a networking concept, or a simple forensic investigation can help many learners.

## About TCOSC

The Tanzania Computing Open Source Community (TCOSC) promotes computing education, practical learning, open-source development, research, and collaboration.

Our community principle is:

**LEARN → PRACTISE → BUILD → SHARE → COLLABORATE → CONTRIBUTE → REVIEW → MAINTAIN → MENTOR**

We encourage members to practise independently, document their experiences, learn from others, and contribute to a shared body of technical knowledge.

Explore our GitHub organisation:

https://github.com/tanzania-computing-open-community

---

**Solve challenges. Understand the techniques. Share what you learn. Help others grow.**
