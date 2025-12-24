+++
title = "Australian Red Cross Blood Service"
date = 2016-10-28
description = "Database file containing personal and health information of 550,000 blood donors was inadvertently placed on a public web server by a third-party contractor, described as Australia's largest security breach at the time."
draft = false

[taxonomies]
sector = ["Health"]
year = ["2016"]

[extra]
severity = "Serious"
data_types = ["Physical Address", "Date of Birth", "Email Address", "Phone Number", "Health Records"]
attack_vector = "Misconfiguration"
official_status = "Investigation Closed"
source_url = "https://www.oaic.gov.au/privacy/privacy-assessments-and-decisions/privacy-decisions/Investigation-inquiry-reports/donateblood.com.au-data-breach-australian-red-cross-blood-service"
archive_link = "https://web.archive.org/web/20240000000000*/https://www.oaic.gov.au/privacy/privacy-assessments-and-decisions/privacy-decisions/Investigation-inquiry-reports/donateblood.com.au-data-breach-australian-red-cross-blood-service"

[extra.impact]
affected_individuals = 550000
individuals_note = "Prospective blood donors who registered via DonateBlood.com.au between 2010 and September 2016"
data_volume_gb = 0
record_count = 550000
financial_cost_total = 0
ransom_demanded = 0
ransom_paid = 0
estimated_remediation = 0
downtime_hours = 0
downtime_note = ""
+++

## Summary

On 28 October 2016, the Australian Red Cross Blood Service disclosed that a database file containing personal and health information of approximately 550,000 prospective blood donors had been publicly accessible on a web server since 5 September 2016. A third-party contractor, Precedent Communications, had inadvertently placed the unencrypted file on a public-facing server. The breach was discovered by security researcher Troy Hunt and reported via AusCERT, prompting an immediate OAIC investigation into what was described as Australia's largest security breach at that time.

## What Happened

The Australian Red Cross Blood Service operated the DonateBlood.com.au website where prospective donors could register and book appointments to donate blood. On 5 September 2016, an employee of Precedent Communications Pty Ltd, a third-party service provider to the Blood Service, saved a database file to a public-facing web server while performing routine system maintenance.

The file contained registration information for approximately 550,000 individuals who had made appointments to donate blood between 2010 and 5 September 2016. The information included names, addresses, dates of birth, gender, blood types, email addresses, phone numbers, and answers to health screening questions used to determine blood donation eligibility.

The file remained publicly accessible for seven weeks. On 25 October 2016, an individual scanning the internet for security vulnerabilities discovered the exposed database file and made a backup copy. This person then contacted Troy Hunt, a well-known security researcher, who verified the breach and immediately notified the Australian Cyber Emergency Response Team (AusCERT). AusCERT then alerted the Red Cross Blood Service on 26 October 2016.

The Blood Service acted quickly once notified, securing the file and beginning its breach response within hours of being informed.

## Impact on Individuals

The breach exposed highly sensitive information about prospective blood donors. The compromised data included:

- Personal contact information (names, addresses, phone numbers, emails)
- Dates of birth and gender
- Blood types
- Responses to health screening questions about medical conditions, medications, travel history, and lifestyle factors

The health screening responses were particularly sensitive as they revealed private medical information that individuals had provided confidentially as part of the donation eligibility process. This information could potentially be used for identity theft, discrimination, or to cause embarrassment if disclosed.

The Blood Service moved quickly to notify all affected individuals via email and provided guidance on protecting themselves from potential identity theft or misuse of their information. The organisation also established dedicated phone lines to answer questions from concerned donors.

## Organisational Response

**Immediate Actions**: Upon being notified on 26 October 2016, the Blood Service immediately secured the database file and launched an investigation. The organisation publicly disclosed the breach on 28 October 2016, two days after discovery.

**OAIC Investigation**: The Australian Information Commissioner opened a Commissioner-initiated investigation on 27 October 2016, the day after the Blood Service learned of the breach. This decision reflected the large number of affected Australians and the sensitivity of the health information involved.

**Third-Party Accountability**: The investigation found that the breach resulted from human error by Precedent Communications. The contractor had not followed proper procedures when handling the database file during system maintenance.

**Investigation Findings**: The OAIC Commissioner's investigation concluded that overall, the Blood Service acted appropriately and in a timely manner in response to the data breach. The organisation had reasonable security measures in place and took swift action once notified. The breach occurred due to contractor error rather than systemic failures by the Blood Service itself.

**Preventative Measures**: Following the incident, the Blood Service and its contractors implemented additional safeguards including enhanced staff training, stricter protocols for handling sensitive data files, and improved monitoring of contractor activities involving personal information.

**Industry Impact**: The incident reinforced the importance of third-party risk management and the need for organisations to maintain oversight of contractors who handle personal information on their behalf.
