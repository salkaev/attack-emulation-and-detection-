# Security Investigation Library

This repository contains a collection of end‑to‑end security investigations. Each case documents the full incident response workflow: from alert validation and data collection through analysis, IOC extraction, MITRE ATT&CK mapping, to remediation recommendations.

The investigations cover various attack scenarios including malware command‑and‑control, phishing, lateral movement, privilege escalation, and credential theft. All cases are based on realistic simulations and lab environments.


## Repository Contents

- **Investigation write‑ups** – detailed narratives with step‑by‑step analysis, screenshots, and command outputs.
- **Indicators of Compromise (IOCs)** – structured lists of hashes, IP addresses, domains, URLs, file paths, and registry keys.
- **MITRE ATT&CK mappings** – techniques observed per case.
- **Supporting materials** – network packet captures, log excerpts, and malware samples (where applicable).

Each investigation is self‑contained and follows a consistent structure to ensure reproducibility and clarity.


## Structure

All investigations are stored in separate directories. Each directory contains a README file with the full analysis description.


## Tools & Technologies

- Network analysis: Wireshark, tcpdump  
- Threat intelligence: VirusTotal, MISP, AbuseIPDB  
- Malware analysis: PE‑studio, strings, hash calculators  
- SIEM and logging: Splunk Enterprise, Sysmon, Windows Event Logs, PowerShell logging  
- Frameworks: MITRE ATT&CK, Cyber Kill Chain  


## Skills Demonstrated

- Incident triage and alert validation  
- Network traffic analysis (PCAP)  
- Host‑based forensics (processes, registry, file system)  
- Threat intelligence correlation  
- IOC extraction and management  
- Detection engineering (SPL, rule logic)  
- MITRE ATT&CK alignment  
- Technical report writing  
