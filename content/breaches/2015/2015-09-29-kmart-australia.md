+++
title = "Kmart Australia"
date = 2015-09-29
description = "Online shopping platform breach exposing customer purchase details and contact information."

[taxonomies]
sector = ["Retail"]
year = ["2015"]

[extra]
severity = "Minor"
data_types = ["Email Address", "Phone Number", "Physical Address"]
attack_vector = "Hacking"
official_status = "Investigation Closed"
source_url = "https://www.itnews.com.au/news/customer-data-stolen-in-kmart-australia-hack-409944"
archive_link = "https://web.archive.org/web/20150929/www.itnews.com.au/news/customer-data-stolen-in-kmart-australia-hack-409944"

[extra.impact]
affected_individuals = 0
individuals_note = "Only customers who shopped online affected - exact number not disclosed"
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
Kmart Australia's online shopping platform was compromised by attackers who accessed customer names, email addresses, delivery and billing addresses, phone numbers and product purchase details. No credit card or payment information was stolen as Kmart uses a third-party payment gateway that does not store financial details internally.

### What Happened
On 29 September 2015, Kmart discovered unauthorised access to its IBM WebSphere Commerce-based online platform. Attackers exploited vulnerabilities in the product ordering system to extract customer information from a subset of online shoppers. The breach only impacted customers who had made purchases through Kmart's website, not in-store shoppers.

Kmart's online platform is built on IBM's WebSphere Commerce software. The attackers gained access to customer order details and personal information associated with online accounts, but were unable to access payment information as Kmart uses ANZ Bank's CyberSource payments gateway for credit card processing and does not store these details internally.

### Impact on Individuals
Affected customers faced risks including:

- **Spam and phishing:** Exposed email addresses and phone numbers could be used for targeted scam messages
- **Address fraud:** Physical addresses combined with names could be used for identity-related fraud
- **Privacy concerns:** Purchase history revealing shopping preferences and delivery locations

Customers were advised to be alert for suspicious emails or phone calls claiming to be from Kmart and to monitor their accounts for unusual activity.

### Organisational Response
As soon as Kmart Australia became aware of the breach, immediate action was taken to stop further unauthorised access. The company notified the Office of the Australian Information Commissioner and the Australian Federal Police on the same day the breach was discovered. Kmart engaged forensic IT investigators to determine how attackers infiltrated the ordering system and contacted all affected customers by email to inform them of the incident.
