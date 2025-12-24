+++
title = "Australian Census"
date = 2016-08-09
description = "Four DDoS attacks overwhelmed the Australian Bureau of Statistics eCensus system due to IBM's geoblocking failures, taking the national Census offline for nearly two days."
draft = false

[taxonomies]
sector = ["Government"]
year = ["2016"]

[extra]
severity = "Serious"
data_types = []
attack_vector = "DDoS Attack"
official_status = "Investigation Closed"
source_url = "https://www.computerweekly.com/news/450403576/IBM-blamed-for-Australian-census-website-crash"
archive_link = "https://web.archive.org/web/20240000000000*/https://www.computerweekly.com/news/450403576/IBM-blamed-for-Australian-census-website-crash"

[extra.impact]
affected_individuals = 0
individuals_note = "No personal data compromised - DDoS attack prevented service access but did not breach data"
data_volume_gb = 0
record_count = 0
financial_cost_total = 30000000
ransom_demanded = 0
ransom_paid = 0
estimated_remediation = 30000000
downtime_hours = 43
downtime_note = "Census system offline from 7:33pm August 9 until August 11, approximately 43 hours total downtime"
+++

## Summary

On 9 August 2016, the Australian Bureau of Statistics eCensus system experienced four distributed denial-of-service (DDoS) attacks that rendered the national Census website inaccessible for nearly two days. The attacks, which peaked at 7:28pm, overwhelmed the system due to IBM's failure to properly implement geoblocking protection. While no data was breached, the incident sparked the #CensusFail social media outcry and resulted in IBM paying a $30 million settlement for failing to meet its contractual obligations.

## What Happened

The Australian Bureau of Statistics contracted IBM for $9.6 million to deliver the 2016 online Census system. On Census night, 9 August 2016, the system came under a series of DDoS attacks:

- **10:10am**: First small attack caused five minutes of disruption
- **11:45am**: Second attack occurred
- **4:52pm**: Third attack hit the system
- **7:28pm**: Major attack commenced, overwhelming the system by 7:33pm

IBM had been contracted to implement a geoblocking service called "Island Australia" that would filter out international traffic to the Census website. However, the geoblocking system failed at approximately 7:30pm, allowing DDoS traffic to directly impact the servers hosted by IBM.

At 8:09pm, the ABS made the decision to shut down the eCensus system, fearing that confidential information might be downloaded under cover of the DDoS attacks. Subsequent investigation revealed there was no unusual outbound traffic—no information had been compromised or stolen. The system remained offline for nearly two days.

## Impact on Individuals

Unlike a data breach, the DDoS attacks did not compromise any personal information submitted to the Census. The primary impact was the inability of Australian households to complete their Census online during the designated period. The incident caused significant public frustration and eroded confidence in government digital services, spawning the viral hashtag #CensusFail on social media.

The disruption prevented millions of Australians from completing their mandatory Census obligation on the designated night, requiring an extension of the Census period. The incident also damaged public trust in large-scale government IT projects and raised serious questions about outsourcing critical national infrastructure to private contractors.

## Organisational Response

Multiple investigations were launched to determine what went wrong:

**Government Inquiry**: Prime Minister Malcolm Turnbull's special adviser on cyber security, Alastair MacGibbon, conducted an investigation that concluded the outages were preventable and resulted from IBM's failure to deliver on its contractual DDoS mitigation obligations.

**IBM's Accountability**: IBM acknowledged responsibility for the failures and apologised to the Australian public. The company made a substantial financial settlement of $30 million with the Australian Government. Senior IBM personnel changes occurred as a consequence of the failure.

**Technical Findings**: The investigation revealed that IBM had "failed to properly implement" the Island Australia geoblocking service. The system was supposed to automatically filter international traffic but failed at the critical moment when the largest attack occurred.

**No Data Breach**: Importantly, investigators confirmed that despite the DDoS attacks and system shutdown, no Census data was lost, stolen, or compromised. The ABS's decision to shut down the system, while causing extended disruption, successfully protected the confidentiality of submitted information.

**Lessons Learned**: The incident highlighted the risks of outsourcing critical government services and the importance of rigorous testing and fail-safe mechanisms for essential national infrastructure. It also prompted reviews of government IT procurement and oversight processes.
