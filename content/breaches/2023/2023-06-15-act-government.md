+++
title = "ACT Government"
date = 2023-06-15
draft = false

[taxonomies]
sector = ["Government"]
year = ["2023"]

[extra]
severity = "Serious"
data_types = ["Email Address"]
attack_vector = "Hacking"
official_status = "Remediation Complete"
source_url = "https://www.cmtedd.act.gov.au/"
archive_link = "https://web.archive.org/web/20230620000000*/https://www.cmtedd.act.gov.au/"

[extra.impact]
affected_individuals = 0
individuals_note = "ACT Government employees and residents; exact number not disclosed"
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

The ACT Government detected a security breach in its Barracuda email gateway system in June 2023, affecting email screening for various government directorates including Access Canberra, health, and education. Barracuda Networks notified customers on 24 May 2023 of a vulnerability, and the ACT Cyber Security Centre immediately completed a rebuild of the impacted system. Investigation by Mandiant identified infrastructure and malware code overlaps indicating "a high degree of confidence that this is a China-nexus espionage operation." Following completion of phase one of the investigation, there was no definitive evidence of information being removed or misused.

### What Happened

The security breach was detected in a Barracuda email gateway system that supports IT systems for the ACT territory government. Barracuda Networks published a notification on its website on 24 May 2023 that there had been a breach affecting its email security products. The vulnerability had potentially been present since October 2022, when Barracuda first started noticing vulnerabilities in its systems.

The ACT Cyber Security Centre immediately completed a rebuild of the impacted Barracuda system to eliminate any ongoing vulnerability upon learning of the breach. A harms assessment was launched to understand the impact specific to ACT Government systems and what data may have been accessed.

Mandiant, a cybersecurity firm brought in to investigate, identified several infrastructure and malware code overlaps that provided "a high degree of confidence that this is a China-nexus espionage operation," suggesting state-sponsored actors rather than financially motivated criminals.

### Impact on Individuals

As government directorates are linked through the email gateway system—including Access Canberra, health, and education—it was initially unknown how much data was exposed and accessed. The potential scope included communications from various ACT Government services that interact with residents and businesses.

However, the nature of the breach appeared to be espionage-focused rather than aimed at stealing personal information for financial fraud. State-sponsored actors typically target government communications for intelligence gathering rather than individual citizens' personal data.

Following the completion of phase one of the investigation, there continued to be no definitive evidence of any information being removed or misused from the systems, providing some reassurance to potentially affected individuals.

### Organisational Response

The ACT Cyber Security Centre took immediate action to rebuild the compromised Barracuda system upon notification of the vulnerability. The Australian Cyber Security Centre was brought in to investigate the incident alongside Barracuda Networks and Mandiant.

The ACT Government's response demonstrated coordination between territory and federal cybersecurity resources. The immediate system rebuild, whilst disruptive, prevented ongoing unauthorised access and contained the breach.

The incident highlighted the challenges governments face in protecting email systems from sophisticated state-sponsored actors, particularly when vulnerabilities exist in widely used enterprise security products. The potential seven-month window of vulnerability (from October 2022 when Barracuda first noticed issues until the May 2023 breach disclosure) underscored the importance of rapid vendor disclosure and patch deployment.

The government maintained transparency with the public about the investigation's progress, though the inability to definitively determine what data was accessed created uncertainty for potentially affected residents and employees.
