+++
title = "Telstra"
date = 2024-11-25
description = "Employee data breach via compromised test environment affecting 44,000 staff and partners."

[taxonomies]
sector = ["Telecommunications"]
year = ["2024"]

[extra]
severity = "Minor"
data_types = ["Email Address", "Phone Number", "Physical Address"]
attack_vector = "Hacking"
official_status = "Remediation Complete"
source_url = "https://www.telstra.com.au/exchange/telstra-employee-and-partner-data-breach--what-you-need-to-know-"
archive_link = "https://web.archive.org/web/20241125/telstra.com.au/employee-data-breach"

[extra.impact]
affected_individuals = 44000
individuals_note = "Telstra employees and partners only - no customer data compromised"
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
Telstra suffered a data breach affecting approximately 44,000 employees and partners when threat actor "UnicornLover67" gained unauthorised access to a pre-production test environment using stolen credentials. The breach exposed employee contact information but did not compromise customer data, passwords or financial information.

### What Happened
On 25 November 2024, Telstra discovered that a file containing employee data had been listed for sale on a dark web hacking forum. The threat actor "UnicornLover67" claimed to have accessed Telstra's internal systems and exfiltrated data belonging to between 44,000 and 47,300 employees and partners.

The breach occurred when the attacker obtained stolen login credentials and used them to access a pre-production test environment for an internal fault-logging system. Pre-production environments are used for testing and development purposes and may contain copies of production data but typically have reduced security controls compared to live systems.

Telstra immediately restricted access to the compromised environment upon discovery and confirmed that the breach was limited to the test environment and did not extend to customer-facing systems or production databases.

### Impact on Individuals
The breach exposed employee and partner contact information including full names, personal and work email addresses, work mobile phone numbers and a small number of residential addresses. While this is classified as basic contact information, it creates risks for affected employees:

- **Targeted phishing attacks:** Work email addresses and knowledge of Telstra employment enables convincing phishing emails
- **Social engineering:** Combining names, contact details and employer information enables sophisticated impersonation attempts
- **Spam and unwanted contact:** Personal email addresses and phone numbers enable direct harassment or marketing
- **Credential stuffing preparation:** Email addresses can be tested against password databases from other breaches

The breach did not expose passwords, banking details, credit card information or government identity documents such as driver's licences or Medicare numbers. Customer data was not compromised in this incident.

### Organisational Response
Telstra immediately restricted access to the compromised pre-production test environment and launched a comprehensive investigation with external cybersecurity experts. The company published a detailed public statement explaining the incident, the types of data affected and what was not compromised.

Telstra notified all affected employees and partners directly, providing guidance on protecting themselves from potential phishing attempts. The company emphasised that employees should remain vigilant for suspicious emails or messages claiming to be from Telstra or attempting to use their employment as a social engineering tactic.

Telstra worked with law enforcement and regulatory authorities to investigate the breach and implement additional security measures to prevent similar credential-based attacks on test environments. The company reviewed access controls and authentication requirements for all pre-production systems.
