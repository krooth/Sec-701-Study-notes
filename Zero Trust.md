---
tags:
  - General_Security_Concepts
date: 27-02-2024
---

# Zero Trust
- Continuous verification and access control
- Every attempt to access a resource is scrutinized and needs to be authenticated
## Functional Network Planes ##
### Data Plane ###
- Process the frames, packets, and network data
- Processing, forwarding, trunking, encrypting, NAT
### Control Plane ###
- Manage the actions of the data plane
- More concerned with policies and rules, how stuff should be performed
- Routing tables, session tables, NAT tables
## Controlling trust ##
### Adaptive identity ###
- Includes additional information in addition to the ones provided by the client
- It considers the source of the request as well as the requested resources
- Multiple risk indicators - relationship to the organization, physical location, type of connection, IP address, etc.
- Make the authentication stronger if needed
### Threat Scope reduction ##
- Decrease the number of possible entry points
### Policy-drive access control ###
- Combine the adaptive identity with a predefined set of rules

## Security Zones ##
- Brad categorizations provide a security-related foundation
- Trusted vs Untrusted networks
- Internal vs External network
- Marketing, IT, Accounting, Human Resources
## Policy enforcement point
- Subject and systems
	- End users, applications, non-human entities
- Policy enforcement point (PEP)
	- We need to pass this enforcement point to get access the requested resource
- Allow, monitor, and terminate connections
	- Can consist of multiple components working together
# {{References}}
