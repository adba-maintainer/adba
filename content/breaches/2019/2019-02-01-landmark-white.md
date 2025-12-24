+++
title = "LandMark White"
date = 2019-02-01
description = "Property valuation firm's data breach exposed home loan details of 100,000 bank customers."

[taxonomies]
sector = ["Professional Services", "Finance"]
year = ["2019"]

[extra]
severity = "Serious"
data_types = ["Physical Address", "Email Address", "Phone Number", "Income Data", "Bank Account Number"]
attack_vector = "Misconfiguration"
official_status = "Investigation Closed"
source_url = "https://www.smh.com.au/business/banking-and-finance/home-loan-details-of-100-000-customers-hacked-in-major-data-breach-20190201-p50unh.html"
archive_link = ""

[extra.impact]
affected_individuals = 100000
individuals_note = "Bank customers who had properties valued by LandMark White for mortgage applications"
data_volume_gb = 0
record_count = 100000
financial_cost_total = 0
ransom_demanded = 0
ransom_paid = 0
estimated_remediation = 0
downtime_hours = 0
downtime_note = ""

[[extra.legal]]
type = "Regulatory Action"
status = "Concluded"
description = "ASIC investigation into disclosure and IT security practices"
url = ""
+++

### Summary

LandMark White, a major property valuation firm servicing Australian banks, suffered a significant data breach in early 2019 that exposed the personal and financial details of approximately 100,000 home loan customers. The breach compromised property valuations, income information, and loan details for customers of major banks including ANZ, NAB, and Commonwealth Bank. The incident caused LandMark White's shares to plunge and led to banks suspending their use of the valuer, while regulators investigated the company's security practices and disclosure handling.

### What Happened

**Misconfiguration.** LandMark White's systems contained an exposed API (Application Programming Interface) that was left publicly accessible without proper authentication controls. This vulnerability allowed unauthorised parties to access a database containing property valuations and associated customer information compiled for bank mortgage applications. The exposed data included property addresses, customer names, contact details, income information, and loan amounts. LandMark White later admitted it had been aware of IT security weaknesses since 2017—a full year before the breach—but had not adequately addressed them. The stolen data subsequently appeared on the dark web, and the CEO eventually resigned over the handling of the incident.

### Impact on Individuals

* **Comprehensive Financial Exposure:** Property values, loan amounts, income details, and personal information compromised
* **Home Address Details:** Precise property addresses linked to owner contact information
* **Income Data Breach:** Salary and financial capacity information exposed
* **Fraud Targeting:** Combination of property, income, and contact data valuable for targeted scams
* **Dark Web Listing:** Stolen data appeared for sale on criminal marketplaces, creating ongoing risk
* **Multiple Bank Customers:** Affected customers across several major Australian banks

The breach was particularly serious because property valuation data contains a comprehensive financial snapshot useful for identity theft and fraud.

### Response

LandMark White initially requested an ASX trading halt and then extended suspensions multiple times as the full scale of the breach and its handling became apparent. The company engaged cybersecurity forensic experts but faced criticism for what some described as "ill-informed public commentary" about the breach. Major banks including ANZ and NAB immediately suspended their use of LandMark White for property valuations, though some government agencies including Centrelink continued using the service, stating the breach affected only a "very small" portion of their clients. The CEO ultimately resigned, and two directors stepped down from the board. ASIC and the Office of the Australian Information Commissioner investigated LandMark White's IT security practices and its disclosure of the breach. The company's share price dropped significantly, and it faced ongoing regulatory scrutiny. The incident highlighted the risks posed by third-party service providers in the financial services supply chain and the potential consequences of ignoring known IT security weaknesses.
+++
