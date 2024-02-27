---
tags:
  - General_Security_Concepts
date: 27-02-2024
---

# AAA (Authentication, Authorization, Accounting)
## Authentication ##
- Ensure entity trying to authenticate is indeed that said entity
- Password and other authentication factors may be userd
	Certificate Authentication**
	- Helps manage security when having remote devices, ensures devices connecting to our network are authorized.
	- A VPN server adds an additional security for authorized devices to connect to network.
	- To use Certificate Authentication we need a Certificate Authority in our environment. Eg: AD CS(Active Directory Certificate Services), once we have configured that, it's a simple process
		- Create Certificate for a device and digitally sign the cert.
		- Import the certificate to client device.
## Authorization ##
- Specifies our level of access, authorized level of access
- Eg: If our organization is following RBAC (We are granted authority only to resources needed by that role)

## Accounting ##
- Ensures that performed actions cannot be denied or on the flip side actions not performed can't be claimed they have been done so.
- Eg: Login time, Data Access (CRUD )

# {{References}}
- [AAA](https://www.professormesser.com/security-plus/sy0-701/sy0-701-video/authentication-authorization-and-accounting-sy0-701/)