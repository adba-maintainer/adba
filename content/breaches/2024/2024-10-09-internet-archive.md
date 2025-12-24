+++
title = "Internet Archive"
date = 2024-10-09
draft = false

[taxonomies]
sector = ["Technology"]
year = ["2024"]

[extra]
severity = "Serious"
data_types = ["Email Address", "Passwords"]
attack_vector = "Hacking"
official_status = "Investigation Closed"
source_url = "https://www.bleepingcomputer.com/news/security/internet-archive-hacked-data-breach-impacts-31-million-users/"
archive_link = "https://web.archive.org/web/20241000000000*/https://www.bleepingcomputer.com/news/security/internet-archive-hacked-data-breach-impacts-31-million-users/"

[extra.impact]
affected_individuals = 31000000
individuals_note = ""
data_volume_gb = 6.4
record_count = 0
financial_cost_total = 0
ransom_demanded = 0
ransom_paid = 0
estimated_remediation = 0
downtime_hours = 0
downtime_note = ""
+++

## Summary

On 9 October 2024, the Internet Archive's Wayback Machine breach was dramatically announced via JavaScript alert: "Have you ever felt like the Internet Archive runs on sticks and is constantly on the verge of suffering a catastrophic security breach? It just happened. See 31 million of you on HIBP!" The attacker stole a 6.4GB database on 28 September containing 31 million users' email addresses, screen names, password change timestamps, and Bcrypt-hashed passwords. The breach coincided with BlackMeta DDoS attacks (believed unconnected). On 20 October, a second breach compromised the Zendesk support email system.

## What Happened

Attackers stole the Internet Archive's authentication database nine days before public disclosure. The 6.4GB SQL file contained email addresses, screen names, Bcrypt-hashed passwords, and internal data with timestamps through 28 September 2024.

## Impact on Individuals

31 million Internet Archive users had authentication credentials exposed, creating account takeover risks despite Bcrypt password hashing.

## Organisational Response

Internet Archive acknowledged the breach following the JavaScript alert defacement and subsequent Zendesk system compromise on 20 October.
