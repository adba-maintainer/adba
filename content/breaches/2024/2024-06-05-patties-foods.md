+++
title = "Patties Foods"
date = 2024-06-05
draft = false

[taxonomies]
sector = ["Manufacturing"]
year = ["2024"]

[extra]
severity = "Minor"
data_types = ["Email Address", "Bank Account Number"]
attack_vector = "Misconfiguration"
official_status = "Investigation Closed"
source_url = "https://www.cyberdaily.au/security/10673-op-ed-patties-foods-data-leak-proves-cyber-reporting-needs-to-do-better"
archive_link = "https://web.archive.org/web/20240600000000*/https://www.cyberdaily.au/security/10673-op-ed-patties-foods-data-leak-proves-cyber-reporting-needs-to-do-better"

[extra.impact]
affected_individuals = 0
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

## Summary

In June 2024, researcher Jeremiah Fowler discovered non-password-protected databases belonging to Patties Foods (Four'N Twenty, Leggo's, Nanna's) managed by third-party Provenio.ai. The exposure included 524k documents: a logging server with 496,296 records plus 25,800 invoices/distribution records containing vendor contacts, emails, banking account numbers, invoice amounts, supplier information, and employee names. Provenio restricted access within hours of notification. Patties claimed "technically wasn't a breach" but a "data exposure" with no evidence of malicious access.

## What Happened

Non-password-protected cloud databases managed by Provenio.ai for Patties Foods were publicly accessible, exposing business and vendor data.

## Impact on Individuals

Vendor and employee contact information and banking details were exposed but no evidence of malicious access was found.

## Organisational Response

Provenio.ai restricted database access within hours. Patties Foods stated no malicious access occurred.
