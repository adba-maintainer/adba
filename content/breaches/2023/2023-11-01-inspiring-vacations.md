+++
title = "Inspiring Vacations"
date = 2023-11-01
draft = false

[taxonomies]
sector = ["Accommodation & Hospitality"]
year = ["2023"]

[extra]
severity = "Serious"
data_types = ["Passport", "Driver License", "Health Records", "Credit Card"]
attack_vector = "Misconfiguration"
official_status = "Settled"
source_url = "https://www.oaic.gov.au/privacy/privacy-assessments-and-decisions/privacy-decisions/enforceable-undertakings/inspiring-vacations-enforceable-undertaking"
archive_link = "https://web.archive.org/web/20231201000000*/https://www.oaic.gov.au/"

[extra.impact]
affected_individuals = 112000
individuals_note = "112,000 travellers, primarily Australian customers"
data_volume_gb = 26.8
record_count = 112605
financial_cost_total = 0
ransom_demanded = 0
ransom_paid = 0
estimated_remediation = 0
downtime_hours = 0
downtime_note = ""

[[extra.legal]]
type = "Regulatory Action"
status = "Concluded"
description = "Enforceable undertaking accepted by Privacy Commissioner on 22 October 2024"
url = "https://www.oaic.gov.au/privacy/privacy-assessments-and-decisions/privacy-decisions/enforceable-undertakings/inspiring-vacations-enforceable-undertaking"
+++

## Summary

Melbourne-based travel agency Inspiring Vacations experienced a significant data breach in November 2023 when a non-password-protected Amazon Web Services (AWS) database containing 112,605 customer records totalling 26.8GB was discovered publicly accessible. The breach exposed highly sensitive travel documents including passport images, travel visas, COVID certificates, and itineraries with partial credit card numbers. Cybersecurity researcher Jeremiah Fowler discovered and responsibly disclosed the exposed database, leading to its securing.

## What Happened

In November 2023, security researcher Jeremiah Fowler discovered a publicly accessible AWS bucket belonging to Inspiring Vacations that contained personal information of Australian customers. The database was not password-protected, leaving 112,605 records exposed to anyone with internet access.

The exposed database contained 26.8GB of data, including approximately 24,000 itinerary and e-ticket PDF documents. The misconfiguration allowed unauthorised access to highly sensitive travel documents that should have been secured with proper access controls.

## Impact on Individuals

The breach exposed potentially sensitive information including high-resolution passport images, travel visa certificates, driver's licences, COVID vaccination certificates, and itinerary files. Approximately 24,000 documents included partial credit card numbers displayed on booking confirmations.

While Inspiring Vacations later stated that the number of people at risk was "significantly smaller" than initially reported, the exposure of passport images and identity documents created substantial risks for affected customers. These documents could be used for identity theft, fraudulent travel bookings, or other criminal purposes.

## Organisational Response

Upon receiving Fowler's responsible disclosure notice, Inspiring Vacations promptly secured the database from public access. The company notified the Office of the Australian Information Commissioner (OAIC) in December 2023 and discharged its obligations under the Notifiable Data Breaches scheme.

On 22 October 2024, the Privacy Commissioner accepted an enforceable undertaking offered by Inspiring Vacations. The OAIC acknowledged that the company cooperated with inquiries and made efforts to improve its information handling practices and strengthen its information security following the incident.

The breach highlighted the critical importance of properly configuring cloud storage services and implementing access controls on databases containing sensitive customer information.
