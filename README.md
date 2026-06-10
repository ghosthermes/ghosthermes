# Raven Fritz
Technical Generalist & QA Automation
Eugene, OR (Remote) | [Bugcrowd](https://bugcrowd.com/h/Liz_Zelda) | ravenfritz98@gmail.com

I read code, isolate failures, and build the glue that makes systems work. 

My background is in black-box vulnerability research and independent IT escalation. I don't write enterprise software from a blank screen. I specialize in rapid prototyping, using AI to scaffold scripts and automation tools, then manually hardening the logic. I am the person who reviews the stack trace, finds the exact line of Python or Rust causing the crash, and engineers the fix.

### Professional Experience

Systems & Hardware Administrator
Student Cooperative Association | Eugene, OR (Feb 2025 - May 2026)
Built and maintained secure infrastructure for a multi-building residential network.
* Flashed and configured Android devices to GrapheneOS for privacy-centric community hardware.
* Integrated HubSpot, Zapier, and local payment gateways to automate operations.
* Managed bare-metal data recovery and hardware troubleshooting for cooperative members.

Independent Vulnerability Researcher
Remote | Bugcrowd, HackenProof, Immunefi (2022 - Present)
I hunt for the logic errors that automated scanners miss. To date, I have submitted over 15 vetted reports across major platforms. 
* Bypassed authentication on a production banking gateway by injecting custom headers, successfully pulling internal logs and ops data.
* Exploited inconsistent error codes in an automotive tech API to leak state data.
* Built custom recon loops using ffuf, Python, and Bash to map obscure endpoints. 
* Dumped API schemas into local LLMs for pattern recognition, then manually verified leads to filter out hallucinations.

IT Support Contractor
Remote | Upwork (2021 - 2024)
Provided remote infrastructure support and security auditing for a portfolio of small business clients. 
* Conducted website security audits to identify unpatched vulnerabilities and access control flaws.
* Locked down client infrastructure through manual system hardening and user access audits.
* Wrote custom Python scripts to automate repetitive maintenance tasks across the client portfolio.

### Featured Project

adtech-forensics-engine (GitHub: ghosthermes/adtech-forensics-engine)
Playwright | Python | Forensic Verification

Litigation-grade automation built for privacy compliance testing. I engineered this in under 48 hours to meet a strict legal deadline. The goal was catching stealth ad-tech tracking that violates wiretap laws.
* Evidentiary Integrity: Captures HAR files with hash verification and UTC-synchronized timestamps.
* Aggressive Probe Logic: Triggers blur event listeners used by modern trackers to evade basic scanners.
* Consent Mapping: Compares OneTrust/Optanon initialization states against actual tracker firing times to prove consent-less data exfiltration.

This project represents my core workflow. I took a niche legal requirement, leveraged AI to compress the development cycle, and delivered a production-ready QA tool that holds up under adversarial scrutiny.

### Technical Tooling

* Languages: Python, Bash. Strong architectural reading comprehension in Rust and JavaScript.
* Environments: Arch Linux, Windows Server, Proxmox, terminal-first workflows.
* Security & QA: Burp Suite, Playwright, custom automated test harnesses, ffuf.
