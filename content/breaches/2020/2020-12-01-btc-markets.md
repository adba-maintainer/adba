+++
title = "BTC Markets"
date = 2020-12-01
draft = false

[taxonomies]
sector = ["Finance"]
year = ["2020"]

[extra]
severity = "Minor"
data_types = ["Email Address"]
attack_vector = "Misconfiguration"
official_status = "Remediation Complete"
source_url = "https://www.itnews.com.au/news/btc-markets-exposes-customer-names-emails-in-botched-blast-send-558121"
archive_link = "https://web.archive.org/web/20201201/https://www.itnews.com.au/"

[extra.impact]
affected_individuals = 0
individuals_note = "Cryptocurrency exchange users; specific count not disclosed"
data_volume_gb = 0
record_count = 0
financial_cost_total = 0
ransom_demanded = 0
ransom_paid = 0
estimated_remediation = 0
downtime_hours = 0
downtime_note = ""
+++

BTC Markets, Australia's largest cryptocurrency exchange, accidentally exposed customer names and email addresses in a botched bulk email distribution.

### What Happened

BTC Markets made an error when sending a bulk email to customers, exposing recipients' email addresses and names to all other recipients. The error occurred due to improper use of email distribution features—likely using standard CC (carbon copy) instead of BCC (blind carbon copy)—causing all recipients to see each other's contact information.

### Impact on Individuals

Affected cryptocurrency exchange users had their email addresses and names exposed to other users. While this represented a relatively minor data exposure, the cryptocurrency context added sensitivity—revealing that individuals were crypto investors could make them targets for phishing, scams, or social engineering attacks specific to the cryptocurrency space.

### Organisational Response

BTC Markets quickly acknowledged the error and apologised to affected customers. The exchange committed to reviewing email distribution procedures to prevent similar incidents. The breach highlighted the importance of proper email handling even for seemingly routine communications, particularly for financial services providers.
