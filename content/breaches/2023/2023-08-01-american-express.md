+++
title = "American Express (APAC)"
date = 2023-08-01
draft = false

[taxonomies]
sector = ["Finance"]
year = ["2023"]

[extra]
severity = "Serious"
data_types = ["Physical Address", "Bank Account Number", "Tax File Number", "Income Data"]
attack_vector = "Insider Threat"
official_status = "Remediation Complete"
source_url = "https://www.americanexpress.com/"
archive_link = "https://web.archive.org/web/20230805000000*/https://www.americanexpress.com/"

[extra.impact]
affected_individuals = 0
individuals_note = "Asia-Pacific employee base affected; exact number not disclosed"
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

American Express disclosed in August 2023 that sensitive personal details of employees working in the Asia-Pacific region were accessed by a former employee based in India. The data breach, which involved a third-party payroll service, reportedly affected the company's entire APAC employee base. The compromised data allegedly included bank account details, names and addresses, payment histories, and tax file numbers. American Express offered free identity theft protection services to impacted employees.

### What Happened

A former employee of American Express based in India accessed sensitive personal details of Asia-Pacific region employees through what appears to have been improper use of their access to a third-party payroll service. The ex-employee's access to the payroll system allowed them to view and potentially extract sensitive employment and financial information.

The breach was discovered in August 2023, though the timeline of when the unauthorised access occurred was not publicly disclosed. The incident represents a classic insider threat scenario where a departing or former employee misused legitimate access privileges before their access was revoked.

### Impact on Individuals

According to some reports, the company's entire APAC employee base was affected, though American Express disputed the full extent of the breach. The data allegedly accessed included:
- Bank account details
- Names and addresses
- Payment histories
- Tax file numbers

American Express stated that no payment data or bank details were accessed by the former employee and that only "certain colleagues" were impacted, contradicting some of the initial reports about the scope of the breach.

The exposure of tax file numbers is particularly concerning as these are permanent identifiers that cannot be changed, creating long-term identity theft risks. Combined with bank account details and payment histories, the stolen data could enable sophisticated fraud or identity theft schemes.

### Organisational Response

American Express confirmed the data leak and attributed it to the actions of a former employee who had access through a third-party payroll service. The company offered free services to affected employees, including support from RISQ and a company that helps victims of identity theft.

The incident prompted American Express to review its access controls for third-party payroll systems and implement additional monitoring to detect unusual access patterns by employees who are departing or have recently left the organisation.

The breach highlighted the challenges organisations face in managing access to sensitive HR and payroll data, particularly when that data is held or accessed through third-party service providers where the company may have less direct control over access logs and monitoring.
