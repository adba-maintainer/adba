+++
title = "Sydney Tools"
date = 2025-03-15
draft = false

[taxonomies]
sector = ["Retail"]
year = ["2025"]

[extra]
severity = "Severe"
data_types = ["Email Address", "Phone Number", "Physical Address", "Employment History", "Income Data"]
attack_vector = "Misconfiguration"
official_status = "Not Reported"
source_url = "https://cybernews.com/security/sydney-tools-exposed-data-leak/"
archive_link = "https://web.archive.org/web/20250315000000*/https://cybernews.com/security/sydney-tools-exposed-data-leak/"

[extra.impact]
affected_individuals = 0
individuals_note = ""
data_volume_gb = 0
record_count = 34000000
financial_cost_total = 0
ransom_demanded = 0
ransom_paid = 0
estimated_remediation = 0
downtime_hours = 0
downtime_note = ""
+++

## Summary

Sydney Tools, one of Australia's largest professional tools resellers, exposed over 34 million customer order records and more than 5,000 employee records after leaving a Clickhouse database publicly accessible without password protection. The breach, discovered by cybersecurity researchers in March 2025, exposed customer names, email addresses, home addresses, phone numbers, and purchase details, as well as employee information including salaries and sales targets.

## What Happened

In March 2025, cybersecurity researchers from Cybernews discovered that Sydney Tools had left a Clickhouse database unprotected and publicly accessible. The database contained over 34 million records of online purchases and more than 5,000 employee entries. Despite researchers' attempts to contact the company, the exposed database remained accessible, continuing to leak sensitive customer and employee data. The misconfiguration allowed unrestricted access to the database without requiring authentication.

## Impact on Individuals

The breach exposed sensitive information of millions of Sydney Tools customers, including names, email addresses, home addresses, phone numbers, and detailed purchase histories. Over 5,000 current and former employees had their personal information exposed, including names, employment branches, salaries, and sales targets. Security researchers warned that the leaked information could enable highly targeted phishing attacks and identity theft, with particular risk to customers who purchased expensive items and high-earning employees.

## Organisational Response

As of the reporting date in March 2025, Sydney Tools had not secured the exposed database despite notification attempts by security researchers. The company had not made public statements regarding the breach or implemented measures to protect the exposed data.
