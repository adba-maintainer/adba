+++
title = "NSW Health (Frontier Software)"
date = 2023-03-09
draft = false

[taxonomies]
sector = ["Health"]
year = ["2023"]

[extra]
severity = "Serious"
data_types = ["Physical Address", "Phone Number", "Date of Birth", "Tax File Number", "Bank Account Number"]
attack_vector = "Third-Party Breach"
official_status = "Remediation Complete"
source_url = "https://www.health.nsw.gov.au/cyberincident/Pages/frontier-software.aspx"
archive_link = "https://web.archive.org/web/20230315000000*/https://www.health.nsw.gov.au/"

[extra.impact]
affected_individuals = 1600
individuals_note = "Former and current staff employed within NSW Ministry of Health between 2001 and 2015"
data_volume_gb = 0
record_count = 1600
financial_cost_total = 0
ransom_demanded = 0
ransom_paid = 0
estimated_remediation = 0
downtime_hours = 0
downtime_note = ""
+++

### Summary

NSW Health announced in March 2023 that approximately 1,600 former and current staff employed within the Ministry of Health, or whose payroll was processed by the Ministry between 2001 and 2015, were affected by a cyber attack on Frontier Software that occurred at the end of 2021. The compromised data potentially included names, residential addresses, phone numbers, dates of birth, tax file numbers, and bank account details. Frontier Software notified NSW Health of the breach in July 2022, though the payroll system involved had been replaced in 2015 and was no longer in active use.

### What Happened

Frontier Software, a payroll processing provider used by NSW Health between 2001 and 2015, suffered a cyber attack at the end of November 2021. The company retained relevant payroll data in an archived system to enable data retrieval by HealthShare NSW on an as-needed basis.

Frontier Software notified NSW Health in July 2022 that the November 2021 cyber attack had compromised payroll information of approximately 1,600 employees. However, NSW Health did not publicly disclose the breach or notify affected staff until March 2023—approximately 16 months after the attack occurred and 8 months after being notified by Frontier.

The NSW Ministry of Health replaced Frontier Software with StaffLink in 2015, meaning the affected payroll system had been out of active use for six years before the breach occurred. The continued retention of archived payroll data created an ongoing exposure risk that was realized when the legacy system was compromised.

### Impact on Individuals

The breach affected approximately 1,600 current and former staff who were employed from 2001 to 2015 at:
- NSW Ministry of Health
- Senior executive positions at NSW Health
- Mental Health Review Tribunal
- Health Professional Councils Authority
- Official Visitors Programme
- Health Infrastructure
- The former NSW Institute of Psychiatry

The data potentially compromised included:
- Full names
- Residential addresses and phone numbers
- Dates of birth
- Tax file numbers
- Bank account numbers (BSB and account number)

The exposure of tax file numbers is particularly concerning as these are permanent identifiers in the Australian tax system that cannot be changed, creating long-term identity theft risks. Combined with bank account details and full personal information, the stolen data provides criminals with comprehensive financial profiles.

### Organisational Response

Frontier Software took immediate steps to prevent further access to the data, prevent its publication to the dark web, and protect against its misuse. In cases where a tax file number was compromised, Frontier advised the Australian Taxation Office and recommended additional security measures.

Ongoing monitoring confirmed that no data from the breach had been uploaded to the dark web, reducing the risk of widespread distribution.

NSW Health notified affected staff via email, whilst former workers could contact a dedicated helpline. The organisation emphasised that medical records in public hospitals were not affected, and the compromised software was no longer in use by NSW Health.

The significant delay between the breach occurring (November 2021), Frontier's notification (July 2022), and public disclosure (March 2023) raised questions about notification timeliness and transparency in third-party breaches.
