---
tags:
  - General_Security_Concepts
date: 26-02-2024
---

# Security Controls

## Control Categories ##
### Technical Controls ###
- Controls implemented using systems, a technical system is being placed as part of having a security control
- Eg:
	- Group Policies
	- Firewall Policies
- Both are broader part of technical systems the former being Operating System control and the later being Firewall, we can also include others like anti-virus, IDS/IPS....

### Managerial Controls ###
- Administrative Policies/Controls, these are usually policies on how to perform, handle or things no to do.
- Security Policies, they are standard operating procedures.

### Operational Controls ###
- Controls are implemented through people instead of technology.
- Examples of these security guards, Security Awareness Programs

### Physical Controls ###
- Controls limiting physical access to certain area of a resource.
- Eg: Fences, Locks, Badge Readers...
---
## Control Types ###
### Preventive ###
- Limits access to particular access
- Firewall rules preventing access to specific network resource
- Guard Shack
- Door Lock
### Deterrent ###
- Discourages access to resource, however it doesn't block access
- Provides warnings signs of consequences
- Reception
- Splash Screen
### Detective ###
- Identify and possible alerts us in case of breach of access, however it might not prevent access
- Collect and review system logs
- Review login reports
### Corrective ###
- Upon event detection, this type of control helps us restore to known good state.
- Helps minimize downtime
- Restoring from backups/snapshots after ransom
- Use a fire extenguisher
### Compensating ###
- Using other means to control the incident/event temporarily
- Existing controls aren't sufficient
- Bug fix process might take time so other method of exploit mitigation can be put in place
- Generator used after power outage
### Directive Control Types ###
- Direct a subject towards security compliance, it's relatively weak security control.
- Authorized Personnel Only

---
## Example Table ##

| **Control Category** | **Technical Controls** | **Managerial Controls** | **Operational Controls** | **Physical Controls** |
| ---- | ---- | ---- | ---- | ---- |
| **Preventive** | Firewalls, encryption, access control lists (ACLs), intrusion detection/prevention systems (IDS/IPS), password policies, user account management, software configuration management | Security policies, procedures, training programs, risk assessments, security awareness programs | Separation of duties, data classification, Secure data handling practices (Eg: Shredding Documents) | Access control systems, security cameras, alarms, security guards, environmental controls |
| **Deterrent** | Splash Screens | Security awareness programs, training programs, security policies | Reception Desk | Security Camera Warning Signs |
| **Detective** | Log monitoring, intrusion detection/prevention systems (IDS/IPS), vulnerability scanning, malware detection, data breach detection | Security audits, incident response reviews, user activity monitoring | Data reconciliation, security incident detection procedures, performance monitoring | Security camera footage review, access control logs review, environmental monitoring, Motion Detectors |
| **Corrective** | Patch management, system restore, incident response procedures, data recovery | Disciplinary action, policy updates, training revisions | Contacting Authorities | Repairing physical security measures, restoring damaged assets, Fire Extinguisher |
| **Compensating** | Block instead of patch | Separation of duties | Require multiple security staff | Power generator |
| Directive | File Storage Policies | Compliance policies | Security policy training | Sign: Authorized Personnel Only |

---

# {{References}}
