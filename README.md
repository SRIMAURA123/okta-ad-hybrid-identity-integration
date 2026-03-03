# okta-ad-hybrid-identity-integration
Okta – Active Directory Integration Lab

Overview
This project documents my hands-on setup of integrating on-prem Active Directory (lab.local) with Okta using the Okta AD Agent.
The goal was to configure directory synchronization and validate user imports.

What I Implemented
	•	Installed and registered the Okta Active Directory Agent on a domain-joined server.
	•	Connected Active Directory (lab.local) to my Okta tenant.
	•	Scoped specific Organizational Units (OUs) for synchronization.
	•	Selected username format (UPN) for matching.
	•	Configured basic attribute selection for user profiles.
	•	Performed Full Import and Incremental Import.
	•	Reviewed import results (Exact matches).
	•	Confirmed user assignments in Okta.
	•	Verified imported users under Directory → People.

What I Tested
	•	Exact user matching between AD and Okta.
	•	Incremental import behavior.
	•	User status visibility in Okta (Staged / Active).

Screenshots
