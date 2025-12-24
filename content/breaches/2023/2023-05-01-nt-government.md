+++
title = "Northern Territory Government"
date = 2023-05-01
draft = false

[taxonomies]
sector = ["Government"]
year = ["2023"]

[extra]
severity = "Serious"
data_types = ["Date of Birth", "Physical Address", "Medicare Number", "Health Records"]
attack_vector = "Misconfiguration"
official_status = "Remediation Complete"
source_url = "https://health.nt.gov.au/news/2023/historic-health-data-incident-no-ongoing-risk-to-patients"
archive_link = "https://web.archive.org/web/20230525000000*/https://health.nt.gov.au/"

[extra.impact]
affected_individuals = 0
individuals_note = "Thousands of NT patients; exact number not disclosed"
data_volume_gb = 0
record_count = 0
financial_cost_total = 0
ransom_demanded = 0
ransom_paid = 0
estimated_remediation = 0
downtime_hours = 0
downtime_note = ""
+++

### Summary

The Northern Territory Government inadvertently shared thousands of identifiable patient health files with global software vendor InterSystems during a medical records transfer in May 2023. NT Health issued statements indicating there is no ongoing risk to patients and that the department has bolstered internal controls to reduce the likelihood of another privacy breach. Chief Minister Natasha Fyles, who was Health Minister at the time, did not make the incident public, instead referring the matter to Information Commissioner Peter Shoyer. NT Health advised that patients themselves were responsible for checking if their records were involved in the transfer.

### What Happened

The Northern Territory Government inadvertently shared identifiable information of thousands of patients when transferring medical records to InterSystems, a global software vendor. The transfer appears to have been part of a system migration or upgrade project involving patient record management systems.

The data transfer occurred without proper de-identification or anonymisation of patient information, meaning that personal details remained attached to medical records when they were sent to the overseas-based vendor. This violated privacy principles requiring that personal health information be protected and only shared with appropriate safeguards.

The incident came to light in late May 2023 when NT Health issued public statements about the privacy breach. However, Chief Minister Natasha Fyles, who was serving as Health Minister at the time the breach occurred, chose not to make the incident public initially, instead referring the matter to the Territory's Information Commissioner.

### Impact on Individuals

Thousands of NT patients had their identifiable health files inadvertently shared with an overseas software vendor. The exposed information potentially included:
- Patient names
- Dates of birth
- Addresses
- Medicare numbers
- Detailed medical records and health information

The exposure of medical records to an unintended third party represents a serious privacy violation, particularly as health information is among the most sensitive personal data. Patients affected by the breach faced uncertainty about what specific information was shared and how the overseas vendor handled or stored their data.

Notably, NT Health advised that patients themselves were responsible for checking if their records were involved in the transfer, placing the burden on individuals to determine their exposure rather than the department proactively notifying all affected patients.

### Organisational Response

Following exposure of the incident, NT Health told media that work had been done to bolster their "internal controls" to reduce the likelihood of another privacy breach. The department issued statements indicating "there is no ongoing risk to any individual and Territorians can be assured their health data is protected by NT Government ICT controls."

The matter was referred to Information Commissioner Peter Shoyer for investigation and determination of whether privacy obligations were breached. The Commissioner's office would assess whether NT Health took appropriate steps to protect patient information and whether the notification process was adequate.

The incident highlighted systemic issues with data handling during system migrations and vendor engagements, particularly the failure to properly de-identify patient data before external sharing. The decision not to proactively notify all affected patients and instead place responsibility on individuals to check their own exposure drew criticism from privacy advocates.
