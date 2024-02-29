---
tags:
  - General_Security_Concepts
date: 29-02-2024
---

# Change management
- Formal process to having changes in the environment
- Having clear process/policies
	- Includes Frequency, duration ,installation process, rollback procedures
- This process helps in ensuring that changes in an environment won't collapse existing working systems or create problems
## Change Approval Process ##
- A formal process for managing change
	- Avoid downtime, confusion, and mistakes
- A typical approval process
	- Complete the request forms
	- Determine the purpose of the change
	- Schedule a date and time of the change
	- Determine affected systems and the impact
	- Analyze the risk associated with the change
	- Get approval from the change control board
	- Get end-user acceptance after the change is complete
## Ownership ##
- Owner of the data
- Don't usually perform the actual change
- Instead manages the process
## Stakeholders ##
- Impacted parties by the change management process
## Impact Analysis ##
- Determining risk value is essential
	- High
	- Medium
	- Low
- Change can cause problems, and before changing we need to understand the risk of changing vs the solution we're making because of change
## Test results ##
- Sandbox testing environment
	- Safe zone for testing before production
- We do need however to confirm a backout plan, as sandbox might not be a 1-1 exact solution
## Backout plan ##
- Contingency plan, reverting plan
- In case reverting fails we need to have a proper backup
## Maintenance window ##
- Maintenance windows might not be easily available depending on environments, so best time might be during off-hours, holidays
- Time of year considerations
## Standard operating procedure ##
- Change management is critical
- Should be well documented
- Standard process and procedures and should be followed at all times
- Regularly updated

# {{References}}
