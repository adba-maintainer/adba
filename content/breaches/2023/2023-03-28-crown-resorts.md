+++
title = "Crown Resorts"
date = 2023-03-28
draft = false

[taxonomies]
sector = ["Accommodation & Hospitality"]
year = ["2023"]

[extra]
severity = "Serious"
data_types = ["Employment History", "Income Data", "Email Address"]
attack_vector = "Third-Party Breach"
official_status = "Remediation Complete"
source_url = "https://www.crownresorts.com.au/"
archive_link = "https://web.archive.org/web/20230401000000*/https://www.crownresorts.com.au/"

[extra.impact]
affected_individuals = 0
individuals_note = "Employee time and attendance records compromised; some Crown Sydney membership numbers exposed"
data_volume_gb = 0
record_count = 0
financial_cost_total = 0
ransom_demanded = 0
ransom_paid = 0
estimated_remediation = 0
downtime_hours = 0
downtime_note = ""

[extra.threat_actor]
name = "Cl0p"
+++

### Summary

Crown Resorts, a major Australian casino and hospitality operator, disclosed in March 2023 that it was investigating a potential data breach after being contacted by a ransomware group claiming to possess Crown files. The incident was linked to a vulnerability in the GoAnywhere file transfer service used by Crown. The Cl0p ransomware group later published a small number of files to the dark web, including employee time and attendance records and some Crown Sydney membership numbers. No customer data was compromised, and business operations were not impacted.

### What Happened

Crown Resorts was contacted in March 2023 by a ransomware group claiming they had illegally obtained a limited number of Crown files. The incident was related to Crown's use of GoAnywhere, a third-party file transfer service that had been compromised globally by the Cl0p ransomware group.

The Cl0p group exploited a zero-day vulnerability (CVE-2023-0669) in the GoAnywhere file transfer software. Fortra, the company behind GoAnywhere, was first made aware of suspicious activity on 30 January 2023 and released a patch for the vulnerability on 7 February. However, the Cl0p group claimed to have stolen data from more than 130 organisations before and after the patch was released.

After approximately a week of investigation, the Cl0p ransomware group's dark web blog displayed a sample of data allegedly stolen from Crown. The leaked files included employee salary information, reports from casino slot machines, employee time and attendance records, and some membership numbers from Crown Sydney.

### Impact on Individuals

Crown confirmed that no customer data had been compromised in the breach. The exposed data was limited to employee-related information, specifically time and attendance records and salary information, as well as some Crown Sydney membership numbers.

The exposure of employee salary information represents a privacy violation and could lead to embarrassment or workplace tensions if comparative pay information becomes known. However, the absence of more sensitive personal data such as bank account details, home addresses, or identity documents limits the potential for financial fraud or identity theft.

### Organisational Response

Crown stated it was investigating the validity of the ransomware group's claims as a matter of priority. The company confirmed that business operations had not been impacted by the incident and that it was working with law enforcement and had notified gaming regulators about the breach.

Crown's incident was part of a much broader global campaign by the Cl0p ransomware group targeting organisations using the vulnerable GoAnywhere file transfer software. Other organisations affected by the same campaign included mining giant Rio Tinto, consumer goods company Procter & Gamble, and numerous other companies and government agencies worldwide.

The incident highlighted the risks associated with supply chain attacks, where vulnerabilities in widely used third-party software can create pathways for attackers to compromise multiple organisations simultaneously.
