+++
title = "OracleCMS"
date = 2024-04-12
draft = false

[taxonomies]
sector = ["Government"]
year = ["2024"]
threat_actor = ["LockBit"]

[extra]
severity = "Serious"
data_types = ["Phone Number", "Physical Address"]
attack_vector = "Ransomware"
official_status = "Remediation Complete"
source_url = "https://www.cyberdaily.au/security/10441-huge-trove-of-australian-client-data-leaked-following-oraclecms-call-centre-hack"
archive_link = "https://web.archive.org/web/20240412/cyberdaily.au/oraclecms-breach"
+++

### Summary
OracleCMS, an Australian call center management service provider (not affiliated with Oracle Corporation), was attacked by LockBit ransomware on April 4, 2024, resulting in the exposure of data from more than 50 organizations including dozens of Victorian councils. LockBit published over 60 gigabytes of leaked data on April 16, 2024, after ransom negotiations failed, compromising after-hours call center records for government agencies and public services across Australia.

### What Happened
LockBit ransomware gang attacked OracleCMS's systems on April 4, 2024, encrypting data and exfiltrating extensive information about the company's clients and their customers. The attackers listed OracleCMS as a victim on their leak site on April 12, 2024, publishing sample documents including bills and invoices as proof of the breach.

LockBit set a deadline of April 16, 2024 for ransom payment. When OracleCMS refused to pay, the ransomware gang published more than 60 gigabytes of data in a single compressed archive. The leaked data contained a "Clients" directory with over 50 folders representing different organizations, ranging from local councils to senior citizen care services and government entities.

OracleCMS provides after-hours and overflow call center support for Australian councils and public services, handling calls when council offices are closed. This meant the breach affected not only OracleCMS as a company but also the constituents of dozens of government organizations that relied on their services.

### Impact on Individuals
The breach exposed information collected through after-hours call center operations, including:
- Customer names and phone numbers
- Property addresses (for service calls)
- Nature and details of calls made to councils
- Corporate information and contract details
- Invoices and billing information
- Triage process workflows

Affected local councils that issued official data breach notices included:
- Knox City Council
- City of Port Phillip
- Manningham Council
- Whitehorse City Council
- City of Monash
- Campbelltown Council
- Tweed Shire Council
- Dandenong City Council
- City of Sydney
- Kwinana Council
- Moreton Bay Council
- Playford Council
- Latrobe City Council
- Merri-bek Council

The exposure primarily affects residents who contacted their local councils outside business hours for issues such as noise complaints, emergency services, infrastructure problems, or other municipal concerns. While the compromised data is largely contact information, it reveals:
- Where individuals live
- What issues they reported to councils
- Patterns of service requests
- Relationships between residents and local government

For some individuals, the nature of their calls may be sensitive (such as reporting neighbor disputes, safety concerns, or requesting welfare services), and public disclosure could cause embarrassment or privacy violations.

### Organisational Response
OracleCMS disclosed the breach and acknowledged that compromised information may include corporate details, contract information, invoices, and triage workflows. Individual councils issued their own data breach notices to affected residents as required under the Notifiable Data Breaches scheme.

Multiple Victorian councils published public statements and updated their websites with information about the breach, advising affected residents to be cautious of potential phishing attempts or scams using their information.

The widespread impact on government services highlighted the risks of third-party vendors in public service delivery, particularly when a single provider serves numerous government entities. The breach prompted councils to review their vendor security requirements and data handling agreements with external call center providers.

The incident occurred despite LockBit facing significant law enforcement disruption earlier in 2024, demonstrating the ransomware gang's continued operational capability and targeting of Australian organizations.

[extra.impact]
affected_individuals = 0
individuals_note = ""
data_volume_gb = 60
record_count = 0
financial_cost_total = 0
ransom_demanded = 0
ransom_paid = 0
estimated_remediation = 0
downtime_hours = 0
downtime_note = ""
+++
