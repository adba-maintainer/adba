+++
title = "Spruson & Ferguson (IPH Limited)"
date = 2023-04-13
draft = false

[taxonomies]
sector = ["Professional Services"]
year = ["2023"]

[extra]
severity = "Minor"
data_types = ["Email Address"]
attack_vector = "Hacking"
official_status = "Remediation Complete"
source_url = "https://www.spruson.com/cyber-incident-further-update/"
archive_link = "https://web.archive.org/web/20230415000000*/https://www.spruson.com/"

[extra.impact]
affected_individuals = 0
individuals_note = "Limited set of client data and historical financial/corporate information"
data_volume_gb = 0
record_count = 0
financial_cost_total = 2500000
ransom_demanded = 0
ransom_paid = 0
estimated_remediation = 2500000
downtime_hours = 0
downtime_note = ""
+++

### Summary

IPH Limited, the parent company of intellectual property law firms Spruson & Ferguson and Griffith Hack, detected unauthorised access to a portion of its IT environment on 13 March 2023. A forensic investigation revealed that a limited set of data originating from Spruson & Ferguson (Australia) was downloaded by an unauthorised third party. The downloaded data contained information relating to certain clients of that practice, as well as some historical financial and corporate information. IPH estimated $2-2.5 million in non-underlying costs related to the incident response.

### What Happened

On 13 March 2023, IPH Limited detected that a portion of its IT environment had been subject to unauthorised access. The breach was primarily limited to the document management systems of the IPH head office and two IPH member firms in Australia—Spruson & Ferguson (Australia) and Griffith Hack—and the practice management systems of these two member firms.

Upon becoming aware of the incident, IPH immediately isolated these systems and removed them from its network. The company implemented its Business Continuity Plan to maintain operations whilst securing the compromised systems.

A forensic probe into the data breach revealed that whilst multiple systems were accessed, only a limited set of data was actually downloaded. The investigation found no evidence that data stored in any other component of IPH's IT network was accessed by the unauthorised third party during the incident.

### Impact on Individuals

The downloaded data contained information relating to certain clients of Spruson & Ferguson (Australia), as well as some historical financial and corporate information. IPH determined it needed to notify only a small number of individuals whose personal information was contained in the dataset.

As an intellectual property law firm, Spruson & Ferguson handles sensitive client information related to patents, trademarks, and other IP matters. However, the forensic investigation's finding that only a limited dataset was downloaded reduced the overall impact compared to if the entire document management system had been exfiltrated.

### Organisational Response

IPH took immediate action to isolate and remove compromised systems from its network upon detection. The company notified the Office of the Australian Information Commissioner of the incident in accordance with legal requirements.

IPH engaged forensic experts to conduct a comprehensive investigation to determine the scope of the breach and identify what data had been accessed or downloaded. The company contacted the small number of individuals whose personal information was identified in the downloaded dataset.

The Sydney-based firm estimated $2-2.5 million (pre-tax) in non-underlying costs to be incurred in its full-year 2023 accounts related to incident response, forensic investigation, system remediation, and legal compliance activities.

The incident highlighted the importance of network segmentation and rapid response capabilities, as IPH's ability to quickly isolate affected systems likely prevented a more extensive data exfiltration.
