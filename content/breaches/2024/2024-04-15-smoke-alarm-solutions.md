+++
title = "Smoke Alarm Solutions"
date = 2024-04-15
draft = false

[taxonomies]
sector = ["Construction"]
year = ["2024"]

[extra]
severity = "Serious"
data_types = ["Email Address", "Phone Number", "Physical Address"]
attack_vector = "Misconfiguration"
official_status = "Not Reported"
source_url = "https://www.vpnmentor.com/news/report-smokealarmsolutions-breach/"
archive_link = "https://web.archive.org/web/20240415/vpnmentor.com/smokealarmsolutions-breach"
+++

### Summary
Smoke Alarm Solutions, Australia's largest smoke alarm installation and service provider, left a database containing 762,856 documents (107GB) publicly accessible without password protection. Discovered by cybersecurity researcher Jeremiah Fowler in April 2024, the exposure included detailed customer invoices, property addresses, and service records spanning 2021-2024. Despite multiple disclosure attempts over nearly two months, the company's legal representatives claimed the incident did not constitute a notifiable data breach under Australian law.

### What Happened
Cybersecurity researcher Jeremiah Fowler discovered a non-password protected database belonging to Smoke Alarm Solutions that was publicly accessible to anyone on the internet. The misconfigured database contained over 762,000 documents totaling 107GB of customer information collected during the company's smoke alarm installation and compliance inspection services.

Fowler sent responsible disclosure notices to Smoke Alarm Solutions in April 2024, including official support documentation explaining how to restrict public access to the database. However, the exposed database remained accessible for nearly two months after the initial notification, with Fowler sending numerous follow-up emails before the database was finally secured.

The database contained:
- 355,384 documents marked as invoices (2021-2024)
- 24,632 "on site quotes" with customer details
- Compliance reports and electrical safety inspections
- Service records and inspection reports
- Customer names, email addresses, phone numbers, and property addresses

It remains unclear how long the database was publicly exposed before Fowler's discovery or whether other parties accessed the sensitive customer information during the exposure period.

### Impact on Individuals
The breach potentially affected over 355,000 Australian homeowners and property managers who used Smoke Alarm Solutions services between 2021 and 2024. The exposed information included:

- Full names and contact details (email addresses, phone numbers)
- Property addresses where smoke alarms were installed or serviced
- Detailed service records revealing when properties would be occupied
- Compliance inspection dates and results
- Quotes and financial information related to services

The exposure creates several risks for affected individuals:
- **Burglary targeting**: Service schedules and property addresses could enable criminals to identify when homes might be unoccupied
- **Targeted scams**: Detailed knowledge of smoke alarm services could facilitate convincing impersonation scams
- **Privacy invasion**: Home service records reveal personal information about property ownership and maintenance
- **Phishing attacks**: Email addresses combined with service context enable targeted phishing campaigns

Particularly concerning was the exposure of service scheduling information, which could reveal patterns of when properties are occupied or vacant, creating physical security risks beyond typical data breaches.

### Organisational Response
Smoke Alarm Solutions eventually secured the exposed database after receiving multiple disclosure notifications from Jeremiah Fowler over a nearly two-month period. However, the company's response through legal representatives was controversial.

The law firm representing Smoke Alarm Solutions stated: "The alleged incident does not constitute a notifiable data breach under the Act, and therefore the client is not required to notify either the authorities or any individual about such alleged incident."

This position contradicted cybersecurity best practices and raised questions about the company's interpretation of Australia's Notifiable Data Breaches (NDB) scheme. The exposure of hundreds of thousands of customer records with names, addresses, and contact information for an extended period would typically trigger NDB obligations if unauthorized access was likely.

The company's decision not to notify affected customers or report to the Office of the Australian Information Commissioner drew criticism from privacy advocates and cybersecurity experts. Affected individuals were left uninformed about the exposure and unable to take protective measures against potential scams or security risks.

The delayed response to initial disclosure attempts—taking nearly two months to secure the database—suggested inadequate security monitoring and incident response procedures. The incident highlighted risks when service providers handling sensitive customer data fail to implement basic security measures like password protection on databases.

[extra.impact]
affected_individuals = 355384
individuals_note = ""
data_volume_gb = 107
record_count = 762856
financial_cost_total = 0
ransom_demanded = 0
ransom_paid = 0
estimated_remediation = 0
downtime_hours = 0
downtime_note = ""
+++
