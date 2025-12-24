+++
title = "Toyota Australia"
date = 2023-05-12
draft = false

[taxonomies]
sector = ["Retail"]
year = ["2023"]

[extra]
severity = "Minor"
data_types = ["Email Address", "Physical Address", "Phone Number"]
attack_vector = "Misconfiguration"
official_status = "Remediation Complete"
source_url = "https://www.toyota.com.au/"
archive_link = "https://web.archive.org/web/20230515000000*/https://www.toyota.com.au/"

[extra.impact]
affected_individuals = 0
individuals_note = "A comparatively small number of Australian records impacted; exact number not disclosed"
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

Toyota confirmed in May 2023 that a comparatively small number of Australian customers' records were impacted after a misconfigured cloud database made vehicle and customer data publicly accessible. The global breach primarily affected 2.15 million users in Japan, with vehicle location information exposed for nearly 10 years between November 2013 and April 2023. Australian customers affected had vehicle information and some personal data such as names and contact information exposed, but no personal financial details were compromised.

### What Happened

The incident occurred on Toyota's cloud environment due to a misconfigured database that was mistakenly set to public view. The data was potentially accessible from November 2013 to April 2023, representing a decade-long exposure period.

Initially, Toyota Australia stated that no Australian customers were affected by the breach, which primarily impacted Japanese customers. However, upon continued investigation, Toyota confirmed that "a comparatively small number of Australian records have been impacted." The company did not disclose the exact number of affected Australian customers.

The breach was caused by a cloud configuration error rather than an external cyber attack. The database settings allowed public access to information that should have been private, though there were no reports of malicious use of the exposed data.

### Impact on Individuals

For affected Australian customers, the exposed data potentially included:
- Vehicle information (location data, vehicle identification numbers, device identifiers)
- Personal information (names and some contact information, including postal and email addresses)
- Toyota-issued customer identifying numbers
- Vehicle registration and identifying numbers

Importantly, no personal financial details were compromised in the breach. The exposure period varied, with some customers in Asia and Oceania having information exposed between October 2016 and May 2023.

Whilst vehicle location data and personal contact information do not directly enable financial fraud, they could be used for targeted scams or to track individuals' movements and habits over the multi-year exposure period.

### Organisational Response

Toyota confirmed there have been no reports of malicious use of the exposed data during the years it was publicly accessible. The company corrected the database configuration to prevent public access and conducted investigations to determine the full scope of customers affected globally.

Toyota notified affected Australian customers and apologised for the incident. The company emphasised that the breach was due to a configuration error rather than a sophisticated cyber attack, and implemented measures to prevent similar misconfigurations in future.

The incident was part of a series of data security issues at Toyota in 2023, highlighting the importance of proper cloud security configurations and regular audits of database access controls.
