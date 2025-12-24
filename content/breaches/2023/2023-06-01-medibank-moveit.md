+++
title = "Medibank (MOVEit)"
date = 2023-06-01
draft = false

[taxonomies]
sector = ["Health"]
year = ["2023"]

[extra]
severity = "Minor"
data_types = ["Email Address", "Phone Number"]
attack_vector = "Third-Party Breach"
official_status = "Remediation Complete"
source_url = "https://www.medibank.com.au/"
archive_link = "https://web.archive.org/web/20230610000000*/https://www.medibank.com.au/"

[extra.impact]
affected_individuals = 0
individuals_note = "Employee data only; no customer data affected"
data_volume_gb = 0
record_count = 0
financial_cost_total = 0
ransom_demanded = 0
ransom_paid = 0
estimated_remediation = 0
downtime_hours = 0
downtime_note = ""

[extra.threat_actor]
name = "Cl0p"
+++

### Summary

Medibank disclosed in June 2023 that a file containing employee names, email addresses, and phone numbers was stolen after its property manager, which used the MOVEit file transfer software, was compromised by the Cl0p ransomware group. No customer data was affected, and Medibank's own systems were not directly impacted by the MOVEit cyberattack. This incident occurred whilst Medibank was still managing the aftermath of a major October 2022 breach that had affected 9.7 million customers.

### What Happened

Medibank's property manager used the MOVEit file transfer software, which was compromised globally by the Cl0p ransomware group exploiting a zero-day vulnerability (CVE-2023-0669) in early 2023. Through this supply chain attack on the property manager's systems, a file containing Medibank employee information was stolen.

The file contained employee names, email addresses, and phone numbers, but did not include employee bank details, payroll information, or home addresses. Medibank confirmed that no customer data was compromised and that Medibank's own systems had not been impacted by the MOVEit cyberattack.

### Impact on Individuals

The breach affected Medibank employees only, with no impact on customers. The compromised data was limited to contact information: names, email addresses, and phone numbers. Whilst this information could potentially be used for targeted phishing or social engineering attacks against Medibank staff, the absence of financial or sensitive personal data reduces the immediate risk of identity theft or fraud.

### Organisational Response

The incident came at a particularly difficult time for Medibank, which was dealing with the ongoing fallout from a major cyber incident it suffered in October 2022. In that earlier breach, data belonging to approximately 9.7 million current and former customers was compromised, including highly sensitive health information. Medibank was facing three class action lawsuits related to the 2022 breach and was under investigation by the country's privacy regulator regarding its handling of personal information.

The MOVEit incident highlighted the ongoing challenges organisations face from supply chain attacks, where third-party vendors' security vulnerabilities can create pathways to access an organisation's data. The MOVEit hack affected hundreds of organisations globally, including British Airways, the BBC, and several US government departments, demonstrating the widespread impact of software supply chain attacks.

Medibank stated it was working with its property manager to understand the full scope of the breach and ensure appropriate security measures were implemented.
