+++
title = "Perpetual"
date = 2023-06-06
draft = false

[taxonomies]
sector = ["Finance"]
year = ["2023"]

[extra]
severity = "Serious"
data_types = ["Physical Address", "Bank Account Number"]
attack_vector = "Third-Party Breach"
official_status = "Remediation Complete"
source_url = "https://www.perpetual.com.au/privacy-policy/security/"
archive_link = "https://web.archive.org/web/20230615000000*/https://www.perpetual.com.au/"

[extra.impact]
affected_individuals = 45000
individuals_note = "Clients of Perpetual's funds using the affected unit registry system"
data_volume_gb = 0
record_count = 45000
financial_cost_total = 0
ransom_demanded = 0
ransom_paid = 0
estimated_remediation = 0
downtime_hours = 0
downtime_note = "Extended outage of unit registry system whilst system rebuilt in secure environment"
+++

### Summary

Perpetual, a major Australian financial services provider, experienced an extended outage beginning 6 June 2023 as a result of a security incident affecting a third-party unit registry system used by some of Perpetual's funds. The breach impacted approximately 45,000 clients and resulted in two separate files being compromised: one containing names, surnames, and addresses, and another containing bank account details. Importantly, the bank account numbers were not linked to the personal contact information, limiting the potential for immediate fraud.

### What Happened

The security incident occurred in a unit registry system provided by a third-party supplier that Perpetual used for some of its funds. When Perpetual became aware of the incident on 6 June 2023, the company immediately disconnected from the third party's system for safety and security.

The investigation revealed that two separate and unrelated files may have been compromised:
1. A file containing first names, surnames, and addresses
2. A separate file containing bank account details

Critically, the bank account numbers were not linked to the names and addresses that were also accessed, meaning attackers could not directly match account numbers to specific individuals using only the stolen data.

As a precautionary measure, Perpetual took some of its own core systems offline to prevent any spread of the incident. This action successfully contained the breach to the third-party provider only, preventing compromise of Perpetual's internal systems.

### Impact on Individuals

Approximately 45,000 clients of Perpetual's funds were impacted by the breach. Whilst sensitive client data remained secure and encrypted, some personal information was accessed by the unauthorised party.

The separation of bank account details from identifying personal information provides some protection, as criminals would need additional information from other sources to conduct fraudulent transactions. However, the exposed data could still be used in combination with information from other breaches or for targeted scam attempts.

Affected clients faced the inconvenience of an extended service outage whilst Perpetual worked with the registry provider to rebuild the system in a new, secure environment. During this period, clients experienced disruptions to their ability to access accounts or conduct transactions through the affected system.

### Organisational Response

Perpetual worked closely with the third-party registry provider to rebuild the unit registry system in a new, secure environment. The company maintained the disconnection from the compromised third-party system until confident that security had been fully restored.

Perpetual reached out to affected clients to inform them of the breach and advise them of steps they could take to protect themselves from scam activity. The company emphasised that whilst some personal information had been accessed, sensitive client data remained encrypted and the bank accounts were not linked to contact information.

The extended outage, whilst disruptive to clients, demonstrated Perpetual's commitment to ensuring security before restoring services. The company prioritised thoroughly investigating and remediating the breach over quickly restoring access.

The incident highlighted the risks that financial services firms face from third-party vendors and the importance of having contingency plans for rebuilding critical systems in secure environments when supply chain breaches occur.
