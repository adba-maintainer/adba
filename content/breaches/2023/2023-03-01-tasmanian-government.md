+++
title = "Tasmanian Government"
date = 2023-03-01
draft = false

[taxonomies]
sector = ["Government"]
year = ["2023"]

[extra]
severity = "Serious"
data_types = ["Physical Address", "Date of Birth", "Bank Account Number", "Email Address"]
attack_vector = "Third-Party Breach"
official_status = "Remediation Complete"
source_url = "https://www.premier.tas.gov.au/site_resources_2015/additional_releases/data-breach-update"
archive_link = "https://web.archive.org/web/20230410000000*/https://www.premier.tas.gov.au/"

[extra.impact]
affected_individuals = 150000
individuals_note = "Approximately 150,000 individuals and businesses in Tasmania directly affected"
data_volume_gb = 0
record_count = 16000
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

The Tasmanian Department of Education, Children and Young People was affected by a cyber attack on GoAnywhere MFT, a third-party file transfer service, in March 2023. The Cl0p ransomware group exploited a zero-day vulnerability to steal approximately 16,000 documents and release them online, affecting approximately 150,000 individuals and businesses in Tasmania. The compromised documents included invoices, bank statements, student assistance applications, and personal information including names, addresses, and bank account details.

### What Happened

The breach stemmed from a cyber attack on GoAnywhere MFT, a third-party file transfer service used by the Tasmanian Department of Education, Children and Young People. The attacks were carried out by Russia-linked ransomware gang Cl0p, which exploited a zero-day vulnerability (CVE-2023-0669) found in the GoAnywhere software on 30 January 2023 and later patched on 7 February.

The security flaw enabled attackers to gain remote code execution on unpatched instances of GoAnywhere MFT. The Tasmanian Government initially stated there was no confirmation of the department's information being stolen. However, Technology Minister Madeleine Ogilvie later confirmed on Good Friday that a range of sensitive financial data was accessed and released online.

Approximately 16,000 documents were released by the attackers. The compromised documents included invoices, bank statements, information relating to student assistance applications, and the names and addresses of people connected to the department.

### Impact on Individuals

The Government of Tasmania confirmed that approximately 150,000 individuals and businesses in the island state were directly affected by the hack. The stolen data included names, addresses, school names, names of children, home rooms, year groups, dates of birth, reference numbers, and bank account details.

The exposure of children's information alongside school details created heightened concerns about child safety. The combination of financial information, particularly bank account details, with personal identifying information created risks of financial fraud and identity theft for affected families and businesses.

### Organisational Response

The Tasmanian Government set up a helpline for affected individuals and businesses to contact for information and support. Minister Ogilvie acknowledged the seriousness of the breach and the impact on Tasmanian families and businesses.

The incident was part of a broader global campaign by the Cl0p ransomware group exploiting the GoAnywhere vulnerability, affecting numerous organisations worldwide. The breach highlighted the risks associated with third-party software vulnerabilities and the importance of timely patching of security flaws.
