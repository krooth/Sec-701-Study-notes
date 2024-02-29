---
tags:
  - General_Security_Concepts
date: 29-02-2024
---

# Technical Change Management
 - Tecnical team is concerned with how to implement a change, while change management is mostly concerned with what needs to change
## Allow list / Deny list ##
- Allow list
	- Deny by default
	- Only specific applications are allowed to run
- Deny list
	- Allow by default
	- Denies only specific applications
## Restricted Activities ##
- Scope of a change, which changes are allowed
- Change approval doesn't necessarily mean any change is allowed
- Might be allowed to execute off the book changes if the intended changes require additional changes
## Downtime ##
- Services will eventually be unavailable
- Changes are made usually during non-production time
- If business is 24/7 we'd have secondary system, upgrade/apply changes to the primary and switch back, preferably in an automated way.
- Secondary systems also allow testing changes on the primary system as it buys more time for us and in case of failure we still have the secondary system.
- We need notify and have calendars for changes
## Restarts ##
- Changes commonly require reboot
- Services, some changes may require only service restarts
- Some changes require only restarting application
## Legacy Applications ##
- Documenting systems and understanding the systems  helps with support cycles
## Dependencies ##
- One change may not be possible due to dependencies
- Documenting dependencies can make change planning and implantation smoother 
## Documentation ##
- It can be challenging to keep up with changes
- Updating diagrams
- Updating policies / procedures
## Version Control ##
- Track changes to a config over time
- Router configs
- Patches
- Application registry entries
- Using Version Control systems or built-in systems
# {{References}}
