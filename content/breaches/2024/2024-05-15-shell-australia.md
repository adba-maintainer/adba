+++
title = "Shell Australia"
date = 2024-05-15
draft = false

[taxonomies]
sector = ["Retail"]
year = ["2024"]

[extra]
severity = "Minor"
data_types = ["Email Address", "Phone Number", "Physical Address", "Customer ID"]
attack_vector = "Third-Party Breach"
official_status = "Investigation Closed"
source_url = "https://www.cyberdaily.au/security/10639-aussies-affected-in-alleged-shell-fuel-data-breach"
archive_link = "https://web.archive.org/web/20240500000000*/https://www.cyberdaily.au/security/10639-aussies-affected-in-alleged-shell-fuel-data-breach"

[extra.impact]
affected_individuals = 80000
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

In May 2024, Shell disclosed a data breach affecting approximately 80,000 customers across multiple countries, including Australians shopping at Shell Coles Express locations. The breach occurred through a third-party mystery shopping vendor that experienced a cybersecurity incident. Compromised data included customer names, email addresses, mobile phone numbers, postcodes, and internal customer identifiers ("shopper codes"). Shell emphasized that the breach originated from the vendor's systems rather than Shell's own infrastructure, though the data related to Shell customer loyalty programs.

## What Happened

A threat actor operating under the alias "888" posted a database on BreachForums containing approximately 80,000 rows of Shell customer data in May 2024. The leaked information included customer details from multiple countries including Australia, the United Kingdom, France, India, Singapore, the Philippines, the Netherlands, Malaysia, and Canada.

Sample data published by the threat actor confirmed that Australian customers were included in the breach, with leaked records showing details of individuals shopping at Shell Coles Express locations—Shell's Australian retail fuel partnership with the Coles supermarket chain.

Shell's investigation determined that the breach occurred at a third-party vendor contracted to provide anonymous mystery shopping services globally. Mystery shopping programs involve sending evaluators to retail locations to assess customer service quality, requiring the vendor to maintain databases of shopper information and store visit details.

Shell stated in its security notice that the incident involved "a cyber security incident that has impacted a third-party software from Progress called MOVEit Transfer, which was running on a Shell IT platform" and that "MOVEit Transfer is used by a small number of Shell employees and customers." However, Shell subsequently clarified that the compromised data did not originate from Shell's own systems and that "Shell is not the owner nor controller of the acquired data."

The breach highlights the persistent vulnerability created by the widespread exploitation of the MOVEit Transfer file transfer software, which became a major attack vector in 2023-2024 following the discovery of critical vulnerabilities that were exploited by numerous ransomware and data theft operations.

## Impact on Individuals

The breach affected approximately 80,000 individuals globally who participated in Shell's mystery shopping programs or whose information was held by Shell's mystery shopping vendor. While the total number of Australian victims was not separately disclosed, sample data indicated that Australians shopping at Shell Coles Express locations were among those affected.

Compromised information included:
- **Personal identifiers**: First and last names, customer/shopper codes
- **Contact details**: Email addresses and mobile phone numbers  
- **Location data**: Postcodes
- **Account information**: Customer status and shopper program identifiers

The exposed data created risks for affected customers including:
- **Phishing attacks**: Email addresses and names could be used for targeted phishing campaigns impersonating Shell or Coles Express
- **SMS scams**: Mobile phone numbers enabled text-based phishing (smishing) attacks
- **Social engineering**: The combination of personal details and knowledge that individuals shop at specific Shell locations could facilitate convincing impersonation scams

Notably, the breach did not expose financial information, payment card details, or fuel transaction histories, limiting the potential for direct financial fraud. The data primarily posed risks related to unwanted marketing contact and social engineering attacks leveraging the Shell brand.

## Organisational Response

Shell issued a public statement acknowledging the incident and clarifying that the breach occurred at a third-party mystery shopping vendor rather than within Shell's own systems. The company emphasized that it was "not the owner nor controller of the acquired data" and that the vendor independently experienced the cybersecurity incident.

Shell's response focused on distinguishing between data held in its own systems versus data maintained by third-party service providers, an approach that raised questions about Shell's responsibility for vendor security practices and customer data protection regardless of which entity technically stored the information.

The company did not publicly disclose whether affected customers received individual notification, whether Shell terminated its relationship with the breached mystery shopping vendor, or what contractual security requirements Shell enforces for third-party service providers handling customer-related information.

Shell's reference to the MOVEit Transfer vulnerability suggested that the breach may have been part of the broader wave of MOVEit-related compromises affecting organizations worldwide, though the company ultimately attributed primary responsibility to the vendor rather than to Shell's own security practices.
