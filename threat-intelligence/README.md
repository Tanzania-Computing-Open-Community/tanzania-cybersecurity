# Threat Intelligence

**Tanzania Computing Open Source Community (TCOSC)**

Learn how to collect, investigate, analyse, and share information about cyber threats to help people and organisations understand and respond to digital risks.

## About This Section

Threat intelligence is the process of collecting and analysing information about cyber threats to understand threat actors, their techniques, malicious infrastructure, vulnerabilities, and potential targets.

This section of TCOSC provides a collaborative learning and development space for students, researchers, developers, security practitioners, and other contributors interested in threat intelligence.

Our goal is to build practical knowledge, publish useful research, develop open-source tools, and improve the ability of the Tanzanian computing community to understand the evolving cybersecurity threat landscape.

## Objectives

- Learn the fundamentals and methodologies of cyber threat intelligence.
- Develop practical skills in open-source intelligence (OSINT) and threat research.
- Understand threat actors, tactics, techniques, and procedures (TTPs).
- Investigate suspicious domains, IP addresses, URLs, files, and other indicators of compromise (IoCs).
- Research malware behaviour and phishing campaigns using safe, controlled methods.
- Understand vulnerability intelligence, CVEs, and their security implications.
- Develop tools for collecting, processing, correlating, and presenting threat data.
- Share research, indicators, detection rules, reports, and learning resources.
- Improve threat intelligence relevant to Tanzania, East Africa, and the wider global community.

## Areas of Learning

### 1. Threat Intelligence Fundamentals

Learn the principles and terminology of threat intelligence.

Topics include:
- What cyber threat intelligence is and why it matters.
- Strategic, operational, tactical, and technical intelligence.
- Threat intelligence lifecycle.
- Intelligence requirements and research questions.
- Data, information, intelligence, and analysis.
- Intelligence confidence, reliability, and limitations.
- False positives, uncertainty, and source validation.

### 2. Open-Source Intelligence (OSINT)

Learn how to investigate publicly available information responsibly.

Topics include:
- Domain and DNS research.
- IP address and network intelligence.
- Certificate transparency and internet asset discovery.
- Public code repository and exposed-secret investigations.
- Publicly available technical reports and security advisories.
- Website, email, and phishing infrastructure analysis.
- Source verification, evidence collection, and research documentation.

### 3. Indicators of Compromise (IoCs)

Learn how to identify and interpret technical indicators associated with suspicious or malicious activity.

Examples include:
- IP addresses.
- Domain names and URLs.
- File hashes.
- Email addresses and sender infrastructure.
- Malware signatures and related artefacts.
- Network traffic indicators.
- YARA rules and other detection patterns.

Understand why an indicator must be evaluated in context. An IP address, domain, or hash should not automatically be labelled malicious without sufficient supporting evidence.

### 4. Threat Actors and Adversary Behaviour

Study how attackers operate and how defenders can understand their behaviour.

Topics include:
- Threat actor profiling and attribution limitations.
- Tactics, techniques, and procedures.
- MITRE ATT&CK framework.
- Attack campaign analysis.
- Initial access, persistence, privilege escalation, and lateral movement.
- Command-and-control infrastructure.
- Threat actor infrastructure tracking.
- Defensive detection and mitigation strategies.

### 5. Vulnerability Intelligence

Understand how vulnerability information can support security decisions.

Topics include:
- Common Vulnerabilities and Exposures (CVE).
- Common Vulnerability Scoring System (CVSS).
- Common Weakness Enumeration (CWE).
- Exploit availability and exploitation evidence.
- Vendor security advisories.
- Vulnerability prioritisation and asset exposure.
- Known Exploited Vulnerabilities (KEV).
- Vulnerability intelligence feeds and automated processing.

A vulnerability's severity score alone does not establish the likelihood that a particular organisation will be attacked. Exposure, exploitability, affected assets, and available mitigations also matter.

### 6. Malware and Phishing Intelligence

Study malicious software and phishing campaigns using controlled, authorised environments.

Topics include:
- Malware families and behaviour.
- File metadata and hash analysis.
- Phishing email and URL analysis.
- Malicious document investigation.
- Sandbox reports and behavioural observations.
- Malware communication patterns.
- Campaign infrastructure and related indicators.
- Defensive signatures and detection opportunities.

**Safety rule:** Do not execute unknown files on personal or production systems. Use isolated analysis environments and follow applicable laws and responsible research practices.

### 7. Threat Intelligence Platforms and Data Formats

Learn how threat data is represented, exchanged, and managed.

Topics include:
- Structured threat information.
- Threat intelligence feeds and APIs.
- STIX and TAXII.
- MISP and collaborative threat sharing.
- Indicator enrichment and correlation.
- Data normalisation, deduplication, and expiration.
- Confidence scoring and provenance.
- Threat intelligence storage and visualisation.

### 8. Detection Engineering and Threat Hunting

Turn intelligence into practical defensive capabilities.

Topics include:
- Mapping threat behaviour to MITRE ATT&CK.
- Writing and testing YARA rules.
- Sigma detection rules.
- Log analysis and event correlation.
- Network traffic investigation.
- Threat hunting hypotheses.
- Detection coverage and validation.
- Measuring false positives and detection gaps.

### 9. Threat Intelligence Automation

Build software that helps analysts collect and process threat information.

Topics include:
- Python and scripting for threat research.
- Public API integration.
- Data extraction and enrichment.
- Automated feed ingestion.
- Indicator correlation and reputation checks.
- Scheduled data processing.
- Dashboards, reports, and visualisation.
- Data quality, caching, and error handling.

Respect each provider's terms of service, API limits, privacy requirements, and data-sharing restrictions.

### 10. Regional and Community Threat Research

Investigate cybersecurity issues affecting Tanzania, East Africa, and other communities.

Possible research areas include:
- Phishing and online fraud trends.
- Threats targeting educational institutions.
- Publicly reported data breaches.
- Commonly exploited technologies.
- Regional internet infrastructure observations.
- Security advisories affecting widely used software.
- Local-language phishing and social engineering patterns.
- Defensive guidance for small organisations and community projects.

Research must be evidence-based. Do not publish unsupported allegations, private personal information, or claims identifying an individual as a threat actor without adequate evidence and a legitimate basis.

## Recommended Learning Resources

The resources below provide documentation, research platforms, datasets, and practical learning environments. Some services require registration or impose usage limits.

### Foundations and Frameworks

- [MITRE ATT&CK](https://attack.mitre.org/) — Knowledge base of adversary tactics and techniques.
- [NIST Cybersecurity](https://www.nist.gov/cybersecurity) — Cybersecurity research, guidance, and standards.
- [CISA Cybersecurity Advisories](https://www.cisa.gov/news-events/cybersecurity-advisories) — Defensive advisories and technical threat information.
- [FIRST](https://www.first.org/) — Resources for incident response and security teams.
- [ENISA Threat Landscape](https://www.enisa.europa.eu/topics/cyber-threats/threat-landscape) — Threat landscape reports and analysis.

### Threat Intelligence and Research Platforms

- [MISP Project](https://www.misp-project.org/) — Open-source threat intelligence sharing platform.
- [OpenCTI](https://github.com/OpenCTI-Platform/opencti) — Open-source cyber threat intelligence platform.
- [OASIS STIX and TAXII](https://oasis-open.github.io/cti-documentation/) — Standards and documentation for structured threat information exchange.
- [AbuseIPDB](https://www.abuseipdb.com/) — IP address abuse reporting and reputation information.
- [URLhaus](https://urlhaus.abuse.ch/) — Sharing information about URLs associated with malware distribution.
- [PhishTank](https://phishtank.org/) — Community-based phishing URL information.
- [MalwareBazaar](https://bazaar.abuse.ch/) — Malware sample and metadata sharing for security research.
- [VirusTotal](https://www.virustotal.com/) — Multi-engine file and URL analysis service.
- [AlienVault OTX](https://otx.alienvault.com/) — Open threat intelligence sharing and indicator information.

**Important:** Public submissions to third-party analysis services may expose submitted files, URLs, or other information to service operators and other users. Never submit confidential documents, private URLs, credentials, personal data, or proprietary samples without authorisation.

### Vulnerability Intelligence

- [CVE Program](https://www.cve.org/) — Public vulnerability identifiers and records.
- [NIST National Vulnerability Database](https://nvd.nist.gov/) — Vulnerability information and analysis resources.
- [CISA Known Exploited Vulnerabilities Catalog](https://www.cisa.gov/known-exploited-vulnerabilities-catalog) — Vulnerabilities known to have been exploited in the wild.
- [OSV](https://osv.dev/) — Open-source vulnerability database and API.

### Detection and Analysis

- [YARA](https://yara.readthedocs.io/) — Pattern-matching rules for identifying and classifying files.
- [Sigma](https://sigmahq.io/) — Generic detection rules for log events.
- [Zeek](https://zeek.org/) — Network security monitoring and traffic analysis.
- [Suricata](https://suricata.io/) — Network threat detection and security monitoring.
- [CyberChef](https://github.com/gchq/CyberChef) — Data transformation and analysis toolkit.
- [Malware Traffic Analysis](https://www.malware-traffic-analysis.net/) — Network traffic analysis exercises and samples.

### Learning and Practical Exercises

- [Security Onion](https://securityonionsolutions.com/) — Security monitoring and threat-hunting platform.
- [Blue Team Labs Online](https://blueteamlabs.online/) — Practical defensive security exercises.
- [CyberDefenders](https://cyberdefenders.org/) — Blue-team labs and investigation challenges.
- [DFIR Report](https://thedfirreport.com/) — Detailed reports on investigated intrusion activity.

Always check the licensing, access requirements, and safety conditions of a resource before using or redistributing its content.

## Practical Projects

TCOSC contributors are encouraged to learn by building and documenting useful projects.

### Beginner Projects

- **IOC Research Notebook:** Record indicators, sources, collection dates, and confidence assessments.
- **Domain Intelligence Tool:** Collect publicly available DNS and registration-related information where available.
- **Phishing Analysis Guide:** Document a repeatable process for examining suspicious messages and URLs without opening dangerous links.
- **CVE Research Tracker:** Organise public vulnerability advisories by product, severity, and remediation status.
- **Threat Intelligence Glossary:** Build a community-maintained reference for important terms and concepts.

### Intermediate Projects

- **IOC Enrichment Tool:** Enrich indicators using permitted public APIs and document source reliability.
- **Threat Feed Aggregator:** Import, normalise, deduplicate, and track indicators from selected public feeds.
- **Threat Report Parser:** Extract structured information from public advisories and reports.
- **MITRE ATT&CK Mapping Tool:** Map documented adversary behaviours to relevant ATT&CK techniques.
- **Phishing Trend Dashboard:** Visualise appropriately sourced, non-sensitive phishing indicators over time.
- **YARA Rule Repository:** Develop and test defensive rules against authorised samples and datasets.

### Advanced Projects

- **Open Threat Intelligence Platform:** Integrate indicator ingestion, enrichment, correlation, search, and reporting.
- **Threat Campaign Correlation Engine:** Identify possible relationships between indicators and campaigns while preserving uncertainty.
- **Vulnerability Intelligence Prioritisation Tool:** Combine public vulnerability data, exploitation evidence, and asset context.
- **Threat Hunting Dataset:** Create documented exercises using authorised logs, packet captures, and forensic artefacts.
- **Regional Threat Landscape Report:** Produce periodic, evidence-based research on cybersecurity trends affecting Tanzania or East Africa.
- **Open-Source Intelligence Pipeline:** Build a modular pipeline with source tracking, data validation, caching, and reproducible reports.

Every project should explain its purpose, installation, data sources, limitations, safety considerations, and how others can reproduce its results.

## How to Contribute

You do not need to be an experienced threat intelligence analyst to contribute.

You can help by:

- Improving documentation and learning materials.
- Reviewing public threat reports and writing evidence-based summaries.
- Adding useful datasets or research references with appropriate licences.
- Developing scripts, APIs, dashboards, and analysis tools.
- Creating detection rules and validating them against authorised datasets.
- Writing practical tutorials and investigation walkthroughs.
- Translating learning resources into accessible languages where permitted.
- Reviewing code, testing projects, and reporting reproducible issues.
- Proposing research questions relevant to the Tanzanian computing community.

### Contribution Process

1. Explore the existing repository and read its contribution guidelines.
2. Choose an existing issue or propose a clearly defined improvement.
3. Create a branch for your work.
4. Make your changes and test them.
5. Document sources, assumptions, limitations, and usage instructions.
6. Submit a pull request describing what changed and how it was validated.
7. Respond constructively to review feedback.

Do not publish copied material without permission or proper attribution. Follow the licence of every dataset, tool, article, and code sample you use.

## Research Quality Standards

All contributions should aim to meet the following standards:

- **Evidence-based:** Support important claims with traceable sources.
- **Reproducible:** Document methods, timestamps, tools, and relevant settings.
- **Context-aware:** Distinguish observed facts from interpretations and hypotheses.
- **Transparent:** State confidence levels, data gaps, and known limitations.
- **Privacy-conscious:** Avoid unnecessary collection or disclosure of personal information.
- **Defensive:** Focus on understanding threats, improving detection, and reducing risk.
- **Maintainable:** Use clear documentation, tests where appropriate, and version control.
- **Responsible:** Follow applicable laws, authorisations, platform terms, and disclosure practices.

Threat intelligence changes over time. Record when information was collected and reviewed, and avoid treating old indicators as permanently valid.

## Ethics and Responsible Research

TCOSC promotes legal, responsible, and community-beneficial cybersecurity research.

Contributors must:

- Use systems and datasets they are authorised to investigate.
- Avoid unauthorised access, disruption, credential theft, and exploitation.
- Protect personal, confidential, and sensitive information.
- Avoid publishing secrets, private identifiers, or unredacted sensitive logs.
- Use isolated environments when handling suspicious files.
- Report discovered vulnerabilities through appropriate responsible disclosure channels.
- Clearly separate verified evidence from speculation.
- Avoid falsely labelling individuals, organisations, or infrastructure as malicious.

If a contribution contains sensitive security information, do not publish it in a public issue or pull request. Use the appropriate private reporting channel established by the affected project or organisation.

## Getting Started

1. Select a topic that matches your current skills and interests.
2. Read the relevant documentation and research examples.
3. Reproduce a small investigation using public, authorised data.
4. Record your methodology, sources, findings, and limitations.
5. Share your learning through a tutorial, tool, dataset, or report.
6. Invite community review and improve your work.

Start small, verify your findings, and build progressively toward more complex research.

## Our Community Principle

**LEARN → PRACTISE → BUILD → SHARE → COLLABORATE → CONTRIBUTE → REVIEW → MAINTAIN → MENTOR**

We believe that open knowledge, practical work, responsible research, and collaboration can help develop sustainable computing and cybersecurity capabilities in Tanzania.

## About TCOSC

The Tanzania Computing Open Source Community (TCOSC) is a community initiative that encourages learning, open-source development, research, collaboration, and contribution across computing disciplines.

Explore our GitHub organisation:

https://github.com/tanzania-computing-open-community

## Licence

Each project, dataset, and research contribution must use a clearly stated licence appropriate to its content and intended use. Contributors should confirm that they have the right to distribute the material they submit.

For code and original documentation, follow the licence selected for this repository and any applicable organisation-wide contribution guidelines.

---

**Learn together. Investigate responsibly. Share intelligence. Build useful tools.**
