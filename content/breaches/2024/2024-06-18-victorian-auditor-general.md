+++
title = "Victorian Auditor-General's Office"
date = 2024-06-18
draft = false

[taxonomies]
sector = ["Government"]
year = ["2024"]

[extra]
severity = "Serious"
data_types = ["Bank Account Number"]
attack_vector = "Social Engineering"
official_status = "Under Investigation"
source_url = "https://www.audit.vic.gov.au/report/assuring-integrity-victorian-governments-procurement-activities"
archive_link = ""

[extra.impact]
affected_individuals = 0
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

## Summary

A June 2024 audit by the Victorian Auditor-General's Office revealed that cyber criminals had accessed Victorian government departments' vendor master file on four occasions over an 18-month period, altering supplier bank account details to redirect payments to fraudulent accounts.

## Attack Vector

Attackers used social engineering techniques to gain access to the central vendor master file database, which holds supplier information including bank account details, ABNs, and invoice records. The criminals then changed bank details in the master file to redirect payments intended for legitimate suppliers to accounts controlled by the attackers.

## Consumer Impact

Government suppliers faced payment disruptions when their legitimate bank details were replaced with fraudulent account information. The incident affected Victorian government procurement processes and highlighted vulnerabilities in vendor payment systems across departments.

## Response

The Victorian Auditor-General's Office recommended that all Victorian government departments adopt data analytics to proactively detect and prevent such fraud. The audit found that while departments have processes for investigating fraud when alerted, only two departments use data analytics to flag unusual or suspicious activity proactively. The report emphasized the need for departments to monitor and manage vendor master files more effectively.
