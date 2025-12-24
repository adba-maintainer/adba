+++
title = "Inspiring Vacations"
date = 2024-01-08
draft = false

[taxonomies]
sector = ["Accommodation & Hospitality"]
year = ["2024"]

[extra]
severity = "Serious"
data_types = ["Passport", "Credit Card", "Email Address", "Phone Number", "Physical Address"]
attack_vector = "Misconfiguration"
official_status = "Settled"
source_url = "https://www.oaic.gov.au/privacy/privacy-assessments-and-decisions/privacy-decisions/enforceable-undertakings/inspiring-vacations-enforceable-undertaking"
archive_link = "https://web.archive.org/web/20240108/oaic.gov.au/inspiring-vacations"

[[extra.legal]]
type = "Regulatory Action"
status = "Concluded"
description = "OAIC enforceable undertaking accepted October 22, 2024"
url = "https://www.oaic.gov.au/privacy/privacy-assessments-and-decisions/privacy-decisions/enforceable-undertakings/inspiring-vacations-enforceable-undertaking"
+++

### Summary
Melbourne-based travel agency Inspiring Vacations exposed the personal information of 112,605 customers through a publicly accessible Amazon Web Services (AWS) S3 storage bucket. The breach, discovered by cybersecurity researcher Jeremiah Fowler in late November 2023, exposed 26.8GB of highly sensitive travel documents including high-resolution passport images, travel visa certificates, and partial credit card numbers.

### What Happened
Inspiring Vacations stored customer data in an AWS S3 cloud storage bucket that was not password-protected, leaving it accessible to anyone on the internet. The misconfiguration allowed unrestricted access to approximately 24,000 itinerary and e-ticket PDFs, along with extensive personal information collected during the travel booking process.

Security researcher Jeremiah Fowler discovered the exposed database in late November 2023 and notified Inspiring Vacations. The company secured the bucket and notified the Office of the Australian Information Commissioner in December 2023. The breach became publicly known in January 2024 when media outlets reported the incident.

The exposure occurred due to improper cloud storage configuration—a common but serious security oversight that left years of customer data vulnerable to unauthorized access by anyone who discovered the unprotected bucket URL.

### Impact on Individuals
The breach exposed extraordinarily sensitive travel and identity information including:
- High-resolution passport images showing full passport details
- Travel visa certificates and immigration documents
- Flight itineraries and e-tickets
- Full names, email addresses, and phone numbers
- Billing and shipping addresses
- Partial credit card numbers
- Travel booking history and preferences

The exposure of passport images is particularly serious as these documents contain enough information for identity theft and cannot be easily changed. Criminals could use high-quality passport scans to create fraudulent identity documents or facilitate illegal border crossings.

The combination of travel itineraries and personal information also creates risks for targeted physical crimes, as malicious actors could identify when individuals would be away from home.

### Organisational Response
Upon notification by the security researcher, Inspiring Vacations immediately secured the exposed AWS bucket and conducted an investigation into the scope of the breach. The company notified the Office of the Australian Information Commissioner and discharged its obligations under the Notifiable Data Breaches scheme.

On October 22, 2024, the Privacy Commissioner accepted an enforceable undertaking from Inspiring Vacations, requiring the company to improve its information handling practices and implement stronger security measures. The OAIC acknowledged that Inspiring Vacations cooperated with inquiries and took steps to enhance its cybersecurity posture.

The enforceable undertaking demonstrates regulatory accountability for failing to properly secure sensitive customer data in cloud storage environments.

[extra.impact]
affected_individuals = 112605
individuals_note = ""
data_volume_gb = 26.8
record_count = 24000
financial_cost_total = 0
ransom_demanded = 0
ransom_paid = 0
estimated_remediation = 0
downtime_hours = 0
downtime_note = ""
+++
