+++
title = "Tangerine Telecom"
date = 2024-02-18
description = "Third-party contractor credential compromise exposing 232,000 customer records."
draft = false

[taxonomies]
sector = ["Telecommunications"]
year = ["2024"]

[extra]
severity = "Serious"
data_types = ["Email Address", "Phone Number", "Physical Address", "Date of Birth", "Customer ID"]
attack_vector = "Third-Party Breach"
official_status = "Remediation Complete"
source_url = "https://www.tangerine.com.au/news/media-statement-tangerine-cyber-incident"
archive_link = "https://web.archive.org/web/20240225/tangerine.com.au/media-statement"
+++

### Summary
Tangerine Telecom, a popular Australian telecommunications provider owned by Commonwealth Bank, experienced a data breach affecting approximately 232,000 current and former customers. The breach occurred when a third-party contractor's credentials were compromised, allowing unauthorized access to a legacy database containing customer information dating from June 2019 to July 2023.

### What Happened
On Sunday, 18 February 2024, an unauthorized party accessed Tangerine's legacy database using compromised credentials belonging to a third-party contractor. The incident was first reported to Tangerine management on Tuesday, 20 February 2024.

The attacker exploited the contractor's credentials to access stored customer data from a database that had been in use between mid-2019 and mid-2023. The compromise was attributed to inadequate credential security at the third-party contractor level.

### Impact on Individuals
The breach exposed:
- Full names and dates of birth
- Mobile phone numbers
- Email addresses and postal addresses
- Tangerine account numbers

**Data NOT compromised:**
- Credit or debit card numbers
- Driver's license numbers or other ID documentation
- Banking details
- Account passwords

With 232,000 affected customers (approximately 0.9% of Australia's population), this represents a significant telecommunications sector breach. While the exposed data does not include financial information or government identity documents, it creates risks for:
- Targeted phishing campaigns using account information
- SIM-swapping attacks using phone number and personal details
- Account takeover attempts
- Identity correlation when combined with other breaches

### Organisational Response
Tangerine took immediate action upon discovery:
- Fully revoked network and systems access for the compromised credentials
- Changed all other team usernames and passwords
- Notified the Australian Cyber Security Centre (ACSC)
- Notified the Office of the Australian Information Commissioner (OAIC)
- Sent email notifications to all 232,000 impacted customers on Wednesday, 21 February 2024

The incident highlighted the risks of third-party contractor access to customer databases and the importance of implementing proper access controls and credential management for external vendors.

[extra.impact]
affected_individuals = 232000
individuals_note = ""
data_volume_gb = 0
record_count = 0
financial_cost_total = 0
ransom_demanded = 0
ransom_paid = 0
estimated_remediation = 0
downtime_hours = 0
downtime_note = ""
+++
