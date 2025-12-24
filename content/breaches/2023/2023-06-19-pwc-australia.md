+++
title = "PwC Australia (MOVEit)"
date = 2023-06-19
draft = false

[taxonomies]
sector = ["Professional Services"]
year = ["2023"]

[extra]
severity = "Minor"
data_types = ["Email Address"]
attack_vector = "Third-Party Breach"
official_status = "Remediation Complete"
source_url = "https://www.pwc.com.au/"
archive_link = "https://web.archive.org/web/20230625000000*/https://www.pwc.com.au/"

[extra.impact]
affected_individuals = 0
individuals_note = "Small number of clients whose files were on MOVEit platform"
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

PricewaterhouseCoopers (PwC) Australia announced on 19 June 2023 that it was impacted by the global MOVEit cyber attack, in which the Cl0p ransomware gang exploited a zero-day vulnerability in Progress Software's managed file transfer solution. PwC used the MOVEit software in a limited number of client engagements, and the company's investigation showed that PwC's own IT network had not been compromised. The company stopped using the software once it learned of the incident and reached out to the small number of clients whose files were impacted.

### What Happened

Beginning on 27 May 2023, the Cl0p ransomware gang began exploiting a previously unknown SQL injection vulnerability (CVE-2023-34362) in Progress Software's MOVEit Transfer, a managed file transfer solution used by organisations worldwide. During the cyber attack, Cl0p exploited this critical zero-day vulnerability to break into the networks of hundreds of organisations and steal their data.

PwC Australia was one of many organisations globally affected by this supply chain attack. The company used MOVEit software "in a limited number of client engagements," meaning the exposure was confined to specific projects rather than across all of PwC's operations.

On 19 June 2023, PwC announced it was impacted by the MOVEit cyber attack. The company's investigation showed that PwC's own IT network had not been compromised, and that the MOVEit vulnerability had a limited impact on the firm. Cl0p claimed to have 120 gigabytes of data from PwC, which it threatened to leak if its demands were not met.

### Impact on Individuals

PwC stated that a small number of clients whose files were stored on the MOVEit platform were potentially affected. The company did not disclose the exact number of affected clients or the specific types of data that may have been accessed.

As a professional services firm, PwC handles sensitive client information including financial records, tax documents, audit materials, and strategic business information. The potential exposure of such data could impact both individual clients and corporate clients, though PwC's statement that the impact was limited to a small number of client engagements suggests the breach was relatively contained.

### Organisational Response

PwC stopped using the MOVEit software once it learned of the vulnerability and incident. The company reached out to the small number of clients whose files were impacted to discuss the incident and provide guidance on protective measures.

PwC's investigation confirmed that its own IT network had not been compromised, meaning the breach was limited to the MOVEit platform rather than representing a broader intrusion into PwC's systems. This containment likely limited the overall damage and exposure.

The incident was part of a massive global campaign by the Cl0p ransomware gang that affected hundreds of organisations worldwide, including other major accounting firms (Ernst & Young), government agencies, universities, healthcare providers, and corporations. The widespread nature of the attack highlighted the significant risks posed by supply chain vulnerabilities in commonly used enterprise software platforms.
