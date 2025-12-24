+++
title = "Vroom by YouX"
date = 2025-03-10
draft = false

[taxonomies]
sector = ["Finance"]
year = ["2025"]

[extra]
severity = "Severe"
data_types = ["Driver License", "Health Records", "Bank Account Number", "Credit Card", "Employment History"]
attack_vector = "Misconfiguration"
official_status = "Remediation Complete"
source_url = "https://cybernews.com/security/australian-fintech-vroom-data-leak/"
archive_link = "https://web.archive.org/web/20250310000000*/https://cybernews.com/security/australian-fintech-vroom-data-leak/"

[extra.impact]
affected_individuals = 0
individuals_note = ""
data_volume_gb = 0
record_count = 27000
financial_cost_total = 0
ransom_demanded = 0
ransom_paid = 0
estimated_remediation = 0
downtime_hours = 0
downtime_note = ""
+++

## Summary

Vroom by YouX, an Australian fintech company providing AI-powered vehicle financing services, exposed 27,000 sensitive customer records through an unsecured Amazon S3 bucket. The publicly accessible database, discovered by cybersecurity researcher Jeremiah Fowler in March 2025, contained driver licences, Medicare cards, bank statements with account numbers, partial credit card numbers, and employment records dating from 2022 to 2025.

## What Happened

In March 2025, cybersecurity researcher Jeremiah Fowler discovered a non-password-protected and unencrypted Amazon S3 bucket belonging to Vroom by YouX, an Australian fintech company formerly known as Drive IQ. The bucket contained 27,000 records including driver licences, Medicare cards, employment statements, and bank statements containing account numbers and partial credit card numbers. An internal screenshot also revealed a MongoDB storage instance containing 3.2 million documents. The exposed records spanned from 2022, when the company launched as Drive IQ, through to 2025.

## Impact on Individuals

The breach exposed highly sensitive financial and identity documents of customers who used Vroom's AI-powered dealership finance platform. The leaked information included driver licences, Medicare cards, bank account numbers, partial credit card numbers, and employment records, creating significant risks for identity theft, fraudulent account creation, unauthorised loan applications, and targeted social engineering attacks.

## Organisational Response

After being notified of the exposure by the researcher, Vroom by YouX responded promptly, stating they had identified and resolved the vulnerability. The organisation committed to conducting a post-incident review to determine appropriate communication plans and implement process improvements. The database was secured shortly after notification.
