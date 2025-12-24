+++
title = "Pizza Hut Australia"
date = 2023-09-01
draft = false

[taxonomies]
sector = ["Accommodation & Hospitality"]
year = ["2023"]
threat_actor = ["ShinyHunters"]

[extra]
severity = "Serious"
data_types = ["Physical Address", "Email Address", "Phone Number", "Credit Card", "Passwords"]
attack_vector = "Misconfiguration"
official_status = "Remediation Complete"
source_url = "https://www.bleepingcomputer.com/news/security/pizza-hut-australia-warns-193-000-customers-of-a-data-breach/"
archive_link = "https://web.archive.org/web/20230921000000*/https://www.bleepingcomputer.com/news/security/pizza-hut-australia-warns-193-000-customers-of-a-data-breach/"

[extra.impact]
affected_individuals = 193000
individuals_note = "193,000 Pizza Hut Australia customers"
data_volume_gb = 0
record_count = 193000
financial_cost_total = 0
ransom_demanded = 0
ransom_paid = 0
estimated_remediation = 0
downtime_hours = 0
downtime_note = ""
+++

## Summary

Pizza Hut Australia confirmed a data breach in September 2023 affecting 193,000 customers after the threat actor ShinyHunters claimed to have stolen data from 1 million customers. The breach occurred between July and August 2023 when unauthorised actors gained access via an unprotected Amazon Web Services (AWS) endpoint. Exposed data included customer names, delivery addresses, email addresses, phone numbers, masked credit card numbers, and encrypted account passwords.

## What Happened

Between July and August 2023, threat actors allegedly gained access to Pizza Hut Australia's customer data through an unprotected Amazon Web Services (AWS) endpoint. The misconfiguration left customer information exposed to unauthorised access.

The notorious data broker ShinyHunters claimed to have stolen data from 1 million customers, though Pizza Hut's investigation confirmed the actual number affected was 193,000 customers. Pizza Hut became aware of the cyber security incident in early September 2023.

## Impact on Individuals

The breach exposed customer names, delivery addresses, email addresses, phone numbers, masked credit card numbers (not full numbers), and encrypted account passwords for online accounts. While credit card numbers were masked and passwords were encrypted using one-way encryption, the exposure of contact information and partial payment details still created risks for affected customers.

Pizza Hut urged customers to stay vigilant for phishing attacks and suspicious links, as the compromised contact information could be used to craft convincing scam messages. The company suggested that recipients of breach notices "may wish to consider" updating their passwords despite the one-way encryption protection.

## Organisational Response

Pizza Hut Australia immediately secured the compromised system upon discovering the breach and launched an investigation with external cybersecurity experts to determine the full scope of the incident.

The company notified 193,000 affected customers and provided guidance on protective measures, including password updates and vigilance against phishing attempts. Pizza Hut emphasised that credit card numbers were masked in its systems and that passwords were protected with one-way encryption, limiting the potential for immediate financial fraud.

The incident highlighted the critical importance of properly securing cloud infrastructure endpoints and implementing defence-in-depth security controls to protect customer data.
