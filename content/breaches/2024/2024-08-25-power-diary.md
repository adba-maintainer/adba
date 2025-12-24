+++
title = "Power Diary"
date = 2024-08-25
draft = false

[taxonomies]
sector = ["Health"]
year = ["2024"]

[extra]
severity = "Minor"
data_types = []
attack_vector = "Misconfiguration"
official_status = "Remediation Complete"
source_url = "https://www1.racgp.org.au/newsgp/professional/patients-sent-spam-emails-in-practice-software-bre"
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

Power Diary, a Ballarat-based practice management software provider serving healthcare clinics in over 23 countries, identified and addressed a spam incident on August 25, 2024. Unauthorized parties triggered the platform's email system to send phishing emails to patients that appeared to come from their healthcare providers.

## Attack Vector

An unauthorized party exploited Power Diary's communication template feature to trigger the sending of spam emails through the platform. The phishing emails mentioned winning an NFT and cryptocurrency award and encouraged recipients to click links claiming fake prizes. The misconfiguration allowed unauthorized email sending without requiring system penetration or data theft.

## Consumer Impact

Phishing emails were sent to patients appearing to originate from their GP or healthcare provider, mentioning cryptocurrency prizes. Only a portion of practices using Power Diary were affected. Critically, the company's investigation confirmed that no personal data was exposed during the incident. The system generated patient-specific details like names only after email sending, meaning unauthorized parties never saw or accessed personal information.

## Response

Power Diary announced the incident on August 25, 2024, and addressed the vulnerability in the email-sending system. All affected practices were notified by email on August 26. The company emphasized that unauthorized parties could not access any personal information of patients or healthcare providers, with the breach limited to unauthorized use of the email communication feature.
