+++
title = "Service NSW"
date = 2023-04-03
draft = false

[taxonomies]
sector = ["Government"]
year = ["2023"]

[extra]
severity = "Minor"
data_types = ["Driver License", "Physical Address"]
attack_vector = "Misconfiguration"
official_status = "Remediation Complete"
source_url = "https://www.service.nsw.gov.au/"
archive_link = "https://web.archive.org/web/20230405000000*/https://www.service.nsw.gov.au/"

[extra.impact]
affected_individuals = 3700
individuals_note = ""
data_volume_gb = 0
record_count = 3700
financial_cost_total = 0
ransom_demanded = 0
ransom_paid = 0
estimated_remediation = 0
downtime_hours = 2
downtime_note = "My Services dashboard taken down for 100 minutes"
+++

### Summary

Service NSW experienced a technical issue on 20 March 2023 caused by a software bug that temporarily allowed logged-in users to view other customers' confidential data through the "My Services" dashboard. The issue lasted 100 minutes and potentially affected 3,700 users, exposing information such as driver's licences, vehicle registration details, vouchers, senior cards, and conveyancing licences. Service NSW confirmed the incident was not a cyber attack but rather a configuration error.

### What Happened

On 20 March 2023, Service NSW experienced a software bug that caused the "My Services" dashboard to temporarily malfunction. The bug resulted in logged-in users being able to view confidential data belonging to other customers when they accessed their dashboard. The types of information that could be viewed included driver's licences, vehicle registration details, various government vouchers, senior cards, and conveyancing licences.

Service NSW became aware of the issue and took the dashboard page down at 3pm. The technical issue lasted approximately 100 minutes before it was resolved. Service NSW confirmed that the incident was not a cyber attack from an external threat actor, but rather an internal technical error caused by a software configuration problem.

### Impact on Individuals

Service NSW stated that the issue may have impacted approximately 3,700 users. Because users had to be logged into the Service NSW system to potentially view other people's information, the exposure was limited to authenticated users during the specific 100-minute window when the bug was active.

The exposed information included government-issued identification documents such as driver's licences, which could potentially be used for identity theft if copied or recorded by users who inadvertently saw others' data. However, the data was "only available to another logged-in individual for a short period of time and was not searchable," reducing the likelihood of systematic data harvesting.

### Organisational Response

Service NSW's response to the breach drew criticism from affected customers. The organisation sent emails to impacted users stating they need not take any immediate action, as the personal details were "only available to another logged-in individual for a short period of time and was not searchable."

Service NSW notified the Information and Privacy Commission and affected customers of the incident. The organisation investigated the root cause of the software bug to prevent similar incidents in the future.

Critics noted that despite Service NSW's assurances, the exposure of driver's licence information and other government credentials, even for a brief period, creates potential risks for affected individuals, particularly if any users took screenshots or otherwise recorded the information they inadvertently accessed.
