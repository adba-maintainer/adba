+++
title = "Sydney Tools"
date = 2024-12-15
description = "Hardware retailer exposed 34 million customer orders through misconfigured database."
draft = false

[taxonomies]
sector = ["Retail"]
year = ["2024"]

[extra]
severity = "Severe"
data_types = ["Email Address", "Physical Address", "Phone Number", "Income Data"]
attack_vector = "Misconfiguration"
official_status = "Not Reported"
source_url = "https://www.cyberdaily.au/security/11902-sydney-tools-exposes-34m-customer-records-after-leaving-database-unprotected"
archive_link = "https://web.archive.org/web/20241220/cyberdaily.au/sydney-tools-database-breach"

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

### Summary
Sydney Tools, a major Australian hardware and DIY supply retailer, left a database containing over 34 million customer order records publicly accessible on the internet. The exposed database also contained sensitive employee information including salaries and sales targets. The breach was discovered by cybersecurity researchers but remained open for an extended period despite attempts to notify the company.

### What Happened
Sydney Tools left a Clickhouse database publicly accessible without authentication, allowing anyone on the internet to access customer and employee data. Security researchers at CyberNews discovered the exposed database and attempted to contact the company, but the database remained accessible and continued leaking data.

The misconfigured database contained:
- Over 34 million online order entries
- Customer purchase histories dating back multiple years
- Employee records including current and past staff

This was not a sophisticated hack—the database was simply left open to the internet without password protection, a fundamental security failure.

### Impact on Individuals

**Customer Data Exposed:**
- Full names and email addresses
- Home addresses and phone numbers
- Complete purchase histories showing items ordered
- Order values and dates

**Employee Data Exposed:**
- Names and surnames
- Branches of employment
- Salaries and sales targets
- Performance data

The breach creates significant risks beyond typical privacy concerns. Criminals now know:
- Which customers purchased expensive power tools, machinery, and equipment
- Where those customers live (potential burglary targets)
- Employee compensation details (enabling targeted social engineering)

The combination of purchase history and home addresses is particularly dangerous—a customer who bought thousands of dollars in professional tools is now a known target for home burglaries.

### Organisational Response
Despite CyberNews researchers attempting to contact Sydney Tools about the exposed database, the company was slow to respond and the database remained publicly accessible. This delay significantly increased the risk to customers and employees, as the longer the database remained open, the more likely it was discovered by criminals.

The incident represents a severe failure in basic database security practices. Unlike sophisticated cyberattacks, this breach was entirely preventable and resulted from not implementing fundamental security controls like authentication and network segmentation.

The exposure of 34 million order records—potentially representing millions of individual customers making multiple purchases—makes this one of the largest Australian retail data exposures by record count, even if the number of unique customers is lower.
