# Security+ Notes — Selecting Effective Security Controls

Tags: #security-plus #fundamentals #security-controls

## Two Ways to Classify Controls

Security controls can be classified along two independent dimensions: **category** (what kind of control it is) and **type** (what function it serves). A single control can be described by both — e.g., a firewall is a *technical* control that's *preventive* in type.

---

## Control Categories

| Category | Description |
|---|---|
| **Technical** | Uses technology — hardware, software, firmware — to reduce risk |
| **Managerial** | Documented in an organization's security policy; focuses on managing risk at a planning/governance level |
| **Operational** | Ensures day-to-day operations comply with policy; implemented by people |
| **Physical** | Impacts the physical world — locks, fences, and similar objects |

---

## Control Types

| Type | Description |
|---|---|
| **Preventive** | Attempts to prevent an incident from occurring |
| **Detective** | Attempts to detect incidents after they've occurred |
| **Corrective** | Attempts to restore normal operations after an incident occurs |
| **Deterrent** | Attempts to discourage individuals from causing an incident |
| **Compensating** | Alternative control used when a primary control isn't feasible |
| **Directive** | Provides instruction to individuals on how to handle security |

---

## Control Categories — Examples

### Technical Controls
- **Encryption** — a strong technical control protecting the confidentiality of data
- **Antivirus software** — protects against malware infection
- **IDS/IPS** (Intrusion Detection/Prevention Systems) — monitor a network or host for intrusions
- **Firewalls** — network firewalls restrict network traffic
- **Least privilege** — individuals or processes are granted only the privileges they need to perform their assigned tasks or functions

### Managerial Controls
- **Risk assessments** — help organizations quantify and qualify risks
- **Vulnerability assessments** — attempt to discover current vulnerabilities

### Operational Controls
- **Awareness and training** — helps users maintain password security, follow a clean desk policy, and understand threats
- **Configuration management** — uses baselines to ensure systems start in a secure, hardened state
- **Media protection** — uses backups and encryption to protect media containing sensitive information

### Physical Controls
- Barricades, lighting, signs, fences, and more

---

## Control Types — Examples

### Preventive Controls
- **Hardening** — making a system more secure than its default configuration
- **Training** — awareness of vulnerabilities and threats helps prevent incidents
- **Security guards** — prevent and deter many attacks by verifying user identities
- **Account disablement process** — ensures user accounts are disabled when an employee leaves the organization
- **Intrusion prevention systems** — can block malicious traffic before it reaches a network

### Deterrent Controls
- Warning signs
- Login banners

### Detective Controls
- **Log monitoring** — logs record details of activity on systems and networks
- **SIEM** (Security Information and Event Management) — detects trends and raises alerts in real time
- **Security audits** — examine the security posture of an organization
- Video surveillance
- Motion detection

### Corrective Controls
- **Backups and system recovery** — recover data or systems if they're lost or corrupted
- **Incident handling processes** — define steps to take in response to security incidents

### Compensating Controls
- **Time-based one-time password (TOTP)** — e.g., provides access to an employee who hasn't yet received their access card
- **Backup generators** — cover power shortages

### Directive Controls
- Policies, standards, procedures, and guidelines

---

## Quick Recap
- **Category** = *what kind* of control (Technical, Managerial, Operational, Physical)
- **Type** = *what function* it serves (Preventive, Detective, Corrective, Deterrent, Compensating, Directive)
- A control is often described by both at once — e.g., a firewall = Technical + Preventive