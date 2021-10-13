# ams-data-cleaning-challenge

Useful resources:
	- OpenRefine - (https://openrefine.org/download.html)
	- GitHub to push code, may need GitHub desktop to push your work and questions

Need:
	-Client report data
	-Policy type mapping junction table


Challenge:
- Normalize a small set of data to a specific format. 
	- Column renames and re order
	- Standardize phone numbers
	- Standardize email fields with extra characters
	- Remove records with no contact info
	- Show all policy types that did not map correctly
- Apply 2 cross reference mappings for policy types, carrier names and client contact info


Pull from the 'generic_insurance_client_report' the 'Email_Primary', 'Phone_Home', 'Email_Alternate', 'First_Name', 'Last_Name', and 'Phone_Cell' details onto the '1000-generic_insurance_policy_report'. Use the 'ApplicantID' as the Unique Identifyer


Expected output on the '1000-generic_insurance_policy_report'