# Wazuh SOC Home Lab — 12-Lab Series

Hands-on SIEM/SOC lab documenting a full Wazuh deployment: server setup,
Windows endpoint monitoring, Sysmon integration, threat detection, and
compliance workflows. Every lab is self-performed and documented end to
end on a personal lab environment (VirtualBox + Windows endpoint).

## Progress: 1/12 Labs Documented

| # | Lab | Status |
|---|-----|--------|
| 1 | [Wazuh Server Deployment & Windows Agent Enrollment](./lab-01-server-deployment) | ✅ |
| 2 | Agent Groups & Centralized Configuration | ⏳ |
| 3 | Windows Security Events & Failed Logon Detection | ⏳ |
| 4 | Sysmon Installation & Process Event Monitoring | ⏳ |
| 5 | File Integrity Monitoring (FIM) | ⏳ |
| 6 | VirusTotal Integration for Automated Threat Enrichment | ⏳ |
| 7 | Security Configuration Assessment (SCA) & Remediation | ⏳ |
| 8 | Vulnerability Detection | ⏳ |
| 9 | — | ⏳ |
| 10 | — | ⏳ |
| 11 | — | ⏳ |
| 12 | — | ⏳ |

## Environment

- **Hypervisor:** VirtualBox
- **SIEM:** Wazuh 4.14.6 (server OVA)
- **Monitored endpoint:** Windows 10 Pro
- **Telemetry:** Windows Event Logs, Sysmon, FIM (syscheck), VirusTotal enrichment, CIS SCA

> Note: IP addresses, hostnames, and any environment-specific identifiers
> in screenshots/configs throughout this repo have been redacted.

## Structure

Each lab has its own folder containing:
- A short write-up (objective, what was done, key learning)
- Relevant config snippets (generic/redacted)
- Screenshot(s) as evidence

---
*Labs 2–12 to be added as completed.*
