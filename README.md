# ams-data-cleaning-challenge

## Resources Needed

- [OpenRefine](https://openrefine.org/download.html)
- GitHub to push code, may need [GitHub Desktop](https://desktop.github.com/) to submit code and questions.

## Challenge

This is a data cleaning challenge. We're looking for the applicant to review the supplied data files and apply various transformations and cleaning rules to produce a clean output.

Under the `Resources` folder are several files. You will be loading up these files into OpenRefine and applying various data cleaning rules. The files are:

- `1000-generic_insurance_policy_report_expected_output_headers.csv`: This is the target data structure for the output.
- `1000-generic_insurance_policy_report.csv`: This is the data that you will be cleaning.
- ``generic_insurance_client_report.csv`: This is a client report that's associated with the policy report.
- `ams_policy_type_mapping.csv`: This is a mapping file you will use for lookups. 
- `ams_carrier_name_mapping.csv`

Using the supplied data files, meet the following objectives:

- Successfully install OpenRefine and create a new project.
- Remove columns and rename remaining columns on the `1000-generic_insurance_policy_report` to match the structure of `1000-generic_insurance_policy_report_expected_output_headers.csv`.
- Create 3 different cross reference mappings:
	- Map client information from the `generic_insurance_client_report` to  `1000-generic_insurance_policy_report`
	- Map `glovebox_policy_type_id` column from `ams_policy_type_mapping` to `1000-generic_insurance_policy_report`
	- Map `glovebox_carrier_id` column from `ams_carrier_name_mapping` to `1000-generic_insurance_policy_report`
- Standardize the Phone Number columns to remove the `-` character.
- Standardize the date fields.

## Submission Process

Click 'reply all' to the 'GloveBox Interview | Data Challenge' email you received and attach the following:

- JSON file of your Open Refine rules for reference.
- A document recording the steps of the cleaning
- Screenshot the records where:
	- No phone numbers or email address are present
	- 'glovebox_policy_type_id' are blank
	- 'glovebox_carrier_id' are blank

## Questions and Clarifications

If you have additional questions, would like clarification, or need any pointers please open an issue on this repository and tag your point of contact.

Good luck!
