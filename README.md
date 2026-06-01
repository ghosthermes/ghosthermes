# Ghost Hermes (Legal Name Raven Fritz)
**Technical Generalist & QA Automation**
Eugene, OR (Remote) | [Bugcrowd](https://bugcrowd.com/h/Liz_Zelda) | ravenfritz98@gmail.com

I read code, isolate failures, and build the glue that makes systems work. 

My background is in black-box vulnerability research and independent IT escalation. I don't write enterprise software from a blank screen. I specialize in rapid prototyping, using AI to scaffold scripts and automation tools, then manually hardening the logic. I am the person who reviews the stack trace, finds the exact line of Python or Rust causing the crash, and engineers the fix.

---

### Professional Experience

**Independent Vulnerability Researcher**
*Remote | Bugcrowd, HackenProof, Immunefi (2022–Present)*
I hunt for the logic errors that automated scanners miss. To date, I’ve submitted over 15 vetted reports across major platforms. 
* Bypassed authentication on a production banking gateway by injecting custom headers, successfully pulling internal logs and ops data.
* Exploited inconsistent error codes in an automotive tech API to leak state data.
* Built custom recon loops using `ffuf`, `gau`, and Bash to map obscure endpoints. 
* Dumped massive API schemas into LLMs for pattern recognition, then manually verified every lead to filter out hallucinations.

**IT Support Contractor**
*Remote | Upwork (2021–2024)*
Provided remote infrastructure support and security auditing for a portfolio of small business clients. 
* Conducted website security audits to identify unpatched vulnerabilities and access control flaws.
* Handled troubleshooting across Windows and Linux environments.
* Locked down client infrastructure through manual system hardening and user access audits.
* Wrote custom Python scripts to automate repetitive maintenance tasks across the client portfolio.

**Independent IT Support Specialist**
*Eugene, OR (2020–2025)*
Built a localized support business entirely through word-of-mouth referrals. I handled the hardware and OS failures that standard helpdesks escalate.
* Managed bare-metal data recovery and deep registry editing for compromised machines.
* Executed aggressive malware remediation on heavily infected residential and small office systems.
* Configured local networks, routers, and custom Linux environments.

---

### Featured Project

**[adtech-forensics-engine](https://github.com/ghosthermes/adtech-forensics-engine)**  
*Playwright • Python • Forensic Verification*

Litigation-grade automation built for privacy compliance testing. I engineered this in under 48 hours to meet a strict legal deadline. The goal was catching "stealth" ad-tech tracking that violates wiretap laws.

* **Evidentiary Integrity:** Captures HAR files with hash verification and UTC-synchronized timestamps.
* **Aggressive Probe Logic:** Triggers `blur` event listeners used by modern trackers to evade basic scanners.
* **Consent Mapping:** Compares OneTrust/Optanon initialization states against actual tracker firing times to prove consent-less data exfiltration.

This project represents my core workflow. I took a niche legal requirement, leveraged AI to compress the development cycle, and delivered a production-ready QA tool that holds up under adversarial scrutiny.

---

### Technical Tooling

* **Languages:** Python, Bash. Strong architectural reading comprehension in Rust and JavaScript.
* **Environments:** Arch Linux, Windows Server, terminal-first workflows.
* **Security & QA:** Burp Suite, Playwright, custom automated test harnesses.
