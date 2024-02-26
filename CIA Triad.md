---
tags:
  - General_Security_Concepts
date: 26-02-2024
---

# CIA Triad
- Fundamentals of security 
- AKA AIC Triad
## Confidentiality ##
- Prevent access from a confidential information to  unauthorized person or system
- Encryption
	- Encode messages so only certain people can read it
- Access controls
	- Selectively restrict access to a resource
- Two-factory authentication
	- Additional confirmation before disclosing information
## Integrity ##
- Data should never be modified without our knowledge
- Hashing
	- Map data of an arbitrary length to data of a fixed length
- Digital signatures
	- Mathematical scheme to verify the integrity of data
- Certificates
	- combine with a digital signature to verify an individual
- Non-repudiation
	- Ensuring that the person claiming to be someone is really indeed that someone
## Availability ##
- Systems and networks must be available at all times
- Fault-tolerance
- Patching
	- Stable
## Non-repudiation ##
- Unable to deny of actions 
- Sign a contract
	- Signature adds non-repudiation
	- Verifiable by others
- Cryptography
	- Proof of integrity
		- Verify data originally sent is same as data received
	- Hashing
		- Represent data as a short string of text
		- Fingerprinting
		- Since hash changes if data changes, it ensures authenticity
	- Proof of origin
# {{References}}
