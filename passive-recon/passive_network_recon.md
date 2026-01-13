# Passive Network Reconnaissance (No Scanning)

## Objective
In this lab, I focused on understanding how information about a target can be
gathered without directly interacting with its systems.
The goal was to learn how passive reconnaissance works and why it is often
used as the first step in real-world attacks.

This approach does not generate traffic toward the target and relies only on
publicly available information.

---

## Tools Used
For this lab, I did not use any active scanning tools.
I relied only on:
- Web browser
- Public search engines (Google, Bing)
- Publicly available databases
- Basic OSINT techniques

---

## Reconnaissance Techniques

### 1. IP and Domain Identification
I learned that useful information about a company or organization can be found
from public sources such as:
- Official websites
- Job postings
- News articles
- Public documents

From these sources, it is sometimes possible to identify:
- Domain names
- IP address ranges
- Hosting providers

---

### 2. DNS Information (Passive)
Without performing any scans, DNS-related information can still be collected
using public tools and databases, such as:
- Public DNS lookup websites
- Certificate Transparency logs
- Historical DNS records

This type of information may reveal:
- Subdomains
- Mail servers
- External or third-party services

---

### 3. Technology Stack Identification
By analyzing public information, I observed that it is often possible to
identify technologies used by a target, such as:
- Web servers (e.g. Apache, Nginx)
- Frameworks
- Content Management Systems (CMS)
- Cloud providers

Knowing these details can help an attacker plan more targeted attacks later.

---

### 4. Metadata Analysis
I also learned that publicly available documents (such as PDF or DOCX files)
may contain metadata.
This metadata can sometimes reveal:
- Usernames
- Software versions
- Internal file paths

---

## Security Impact
This lab helped me understand that passive reconnaissance is difficult to
detect and can expose a significant amount of information.
If too much information is publicly available, it increases the attack
surface of an organization.

---

## Conclusion
Through this lab, I learned how valuable information can be collected without
sending any packets to the target.
This highlighted the importance of controlling information exposure and
understanding how attackers think during the early stages of an attack.
