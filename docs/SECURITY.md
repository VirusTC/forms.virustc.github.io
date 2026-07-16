# Security & Regulatory Vulnerability Policy

As an organization operating at the intersection of natural pharmacology, synthetic biopharma supply, and clinical compliance, maintaining data integrity and infrastructure security is critical to our partnerships with hospitals, university medical networks, and regulatory bodies.

This document outlines our protocol for reporting, assessing, and resolving security vulnerabilities or data handling anomalies.

---

## Supported Versions

We actively monitor and provide security patches for data schemas, software utilities, and documentation structures within the following operational windows:

| Version | Supported | Maintenance Tier |
| :--- | :---: | :--- |
| v2.4.x / Current |  | Active Security Auditing & Patching |
| v2.3.x | | Critical Exploits Only |
| < v2.2.x | | End of Life (EOL) — Deprecated |

---

## Reporting a Vulnerability or Compliance Anomaly

**Do not open public GitHub Issues for security vulnerabilities or regulatory compliance discrepancies.** 

To protect patient-centric data tracking pipelines and ensure absolute alignment with federal data frameworks, all security findings must be reported through our encrypted clinical reporting channel.

### How to Report
Please send an encrypted email to our data safety infrastructure desk at:  
**`drhofstad@u.washington.edu`**

### What to Include
To accelerate our internal review and remediation process, please structure your report with the following details:
1. **Scope:** The specific repository, asset, or data schema where the anomaly was identified.
2. **Impact:** A brief assessment of how the issue affects data integrity, system uptime, or regulatory compliance (e.g., 21 CFR Part 56 guidelines).
3. **Proof of Concept (PoC):** Step-by-step instructions, raw scripts, or logs required to reproduce the behavior.
4. **Remediation Suggestion:** (Optional) Your technical or structural recommendation for resolving the issue safely.

---

## Our Response and Remediation Lifecycle

When a report is received through our verified channel, our internal compliance and infrastructure teams execute the following multi-step protocol:

1. **Immediate Triage:** Within **24–48 business hours**, our team will acknowledge receipt of the report and initiate a private internal investigation.
2. **Vulnerability Assessment:** We will verify the finding in an isolated sandbox environment to evaluate its potential impact on clinical procurement scripts, hardware firmware, or institutional documentation.
3. **Coordinated Resolution:** A secure patch, revision, or data schema update will be drafted. 
4. **Institutional Notice:** If the vulnerability impacts active supply chains, tracking loops, or data shared with hospital procurement desks, automated notifications will be dispatched directly to designated institutional **Human Protections Administrators** or technical points of contact.
5. **Public Release:** Once fixed, the update will be merged into the public branch with an accompanying entry in our repository `CHANGELOG.md`.

---

## Legal & Compliance Frameworks

Our organization strictly adheres to the ultimate authority of external federal guidelines. We expect all independent security researchers and collaborating academic experts to operate within the following boundaries:
* Avoid accessing, modifying, or destroying live datasets or infrastructure pipelines.
* Do not execute Denial of Service (DoS) testing against active organizational endpoints.
* Ensure all communication remains confidential throughout the designated triage and patch lifecycle window.

Thank you for helping us maintain absolute safety, clinical transparency, and strict regulatory compliance across our open-science frameworks.
