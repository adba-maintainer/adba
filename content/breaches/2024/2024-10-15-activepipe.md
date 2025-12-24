+++
title = "ActivePipe"
date = 2024-10-15
description = "Real estate marketing platform breach through compromised credentials."
draft = false

[taxonomies]
sector = ["Technology"]
year = ["2024"]

[extra]
severity = "Minor"
data_types = ["Email Address", "Phone Number", "Physical Address"]
attack_vector = "Phishing"
official_status = "Not Reported"
affected_parties = ["Finsure"]
source_url = "https://www.cyberdaily.au/security/11422-exclusive-aussie-mortgage-broker-finsure-confirms-cyber-incident-impacting-customers-and-brokers"
archive_link = "https://web.archive.org/web/20241110/cyberdaily.au/finsure-cyber-incident"
+++

### Summary
ActivePipe, a real estate marketing platform used by mortgage brokers and property professionals, experienced a data breach on 15 October 2024 when an unauthorized party accessed the platform using compromised credentials. The breach exposed contact information of approximately 296,000 individuals, primarily customers and brokers of Finsure, an Australian mortgage broking group that used ActivePipe for marketing communications.

### What Happened
On 15 October 2024, an unauthorized party accessed ActivePipe's real estate marketing platform using compromised credentials—most likely obtained through phishing or credential theft. On 6 November 2024, ActivePipe was informed by an aggregator partner that a cybersecurity researcher had accessed basic contact data on the platform.

The compromised data was subsequently added to the "Have I Been Pwned" data breach notification service, listing 296,124 unique email addresses.

**Disputed Scale:** There is significant disagreement about the breach's scope:
- Have I Been Pwned lists nearly 300,000 affected email addresses
- ActivePipe claims only 35 contacts had data requiring notification
- Finsure states the breach involved "a number of" brokers and customers

ActivePipe stated that its platform was not breached and no data for other customers or integrations was affected—only data accessible through the compromised credentials was exposed.

### Impact on Individuals
The compromised data included:
- Email addresses
- Names
- Phone numbers  
- Physical addresses

**Not compromised:**
- Passwords
- Financial data
- Mortgage application details
- Credit information

Finsure stated that the exposed data was "publicly available" information, which is why the company considered it not to meet the threshold for a notifiable data breach under Australian privacy law. However, this classification is debatable as the data was aggregated in a marketing database and not individually "public."

The risk to affected individuals is limited to:
- Increased spam and phishing attempts
- Potential for targeted mortgage/financial scams using the contact information
- Privacy concerns about marketing data exposure

### Organisational Response
ActivePipe confirmed the incident affected marketing data accessed through compromised credentials but maintained that its platform itself was not breached. Finsure, as the primary affected customer, did not notify the Office of the Australian Information Commissioner, taking the position that the exposed data was publicly available.

The incident highlights risks in Software-as-a-Service (SaaS) platforms where:
- Customer data from multiple organizations is stored centrally
- Credential compromise can expose substantial amounts of data
- Responsibility for breach notification may be unclear between the platform provider and the customer organization
- "Publicly available" data classification can be used to avoid breach reporting obligations

The mortgage broking industry's reliance on third-party marketing platforms creates potential vulnerabilities, particularly when those platforms aggregate contact information from thousands of clients and prospects.

[extra.impact]
affected_individuals = 296124
individuals_note = ""
data_volume_gb = 0
record_count = 0
financial_cost_total = 0
ransom_demanded = 0
ransom_paid = 0
estimated_remediation = 0
downtime_hours = 0
downtime_note = ""
+++
