+++
title = "Cupid Media"
date = 2013-11-01
description = "Dating website breach exposing 42 million plaintext passwords and personal details."

[taxonomies]
sector = ["Technology"]
year = ["2013"]

[extra]
severity = "Severe"
data_types = ["Email Address", "Passwords", "Date of Birth", "Physical Address"]
attack_vector = "Hacking"
official_status = "Investigation Closed"
source_url = "https://krebsonsecurity.com/2013/11/cupid-media-hack-exposed-42m-passwords/"
archive_link = "https://web.archive.org/web/20131101/krebsonsecurity.com/2013/11/cupid-media-hack-exposed-42m-passwords/"

[extra.impact]
affected_individuals = 254000
individuals_note = "42 million global users affected, approximately 254,000 Australian customers"
data_volume_gb = 0
record_count = 42000000
financial_cost_total = 0
ransom_demanded = 0
ransom_paid = 0
estimated_remediation = 0
downtime_hours = 0
downtime_note = ""
+++

### Summary
Cupid Media, an Australia-based operator of niche dating websites, suffered a data breach exposing more than 42 million customer records globally, including approximately 254,000 Australians. The breach was particularly severe because passwords were stored in plaintext rather than being encrypted, allowing attackers immediate access to user accounts.

### What Happened
In January 2013, hackers exploited a vulnerability in the Adobe ColdFusion server platform used by Cupid Media's websites. The attackers uploaded a rogue ColdFusion file to the webservers, which allowed them to run repeated database queries and extract customer information without authorisation.

The stolen data included names, email addresses, unencrypted passwords and dates of birth from users of dating sites including AsianDating.com, ChristianCupid.com and Muslima.com. The breach was publicly disclosed in November 2013 when the stolen database appeared online.

Analysis of the leaked passwords revealed poor security practices by users: nearly 2 million people had chosen "123456" as their password, while another 1.2 million used "11111".

### Impact on Individuals
The exposure of plaintext passwords created significant risks for affected users:

- **Account takeover:** Criminals could immediately access dating profiles using the stolen passwords
- **Credential stuffing:** Many people reuse passwords across multiple websites, allowing attackers to potentially access victims' email, banking or social media accounts
- **Privacy violations:** Dating profiles often contain intimate personal information, preferences and private messages
- **Targeted scams:** Email addresses combined with personal details enabled sophisticated phishing and romance scams
- **Blackmail risk:** Information about dating preferences and relationship status could be used for extortion

Users were advised to immediately change passwords on Cupid Media sites and any other services where they had reused the same password.

### Organisational Response
The Australian Privacy Commissioner investigated and ruled that Cupid Media's failure to encrypt stored passwords constituted a breach of the National Privacy Principles. The Commissioner found that Cupid Media "failed to take reasonable steps to ensure the security of the personal information that it held."

However, because the incident occurred prior to the introduction of updated privacy principles in March 2013, Cupid Media was not liable for financial penalties under the old legislation. The company was required to improve its security practices, including implementing proper password encryption for all user accounts.
