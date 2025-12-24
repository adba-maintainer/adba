+++
title = "ZircoDATA"
date = 2024-02-08
draft = false

[taxonomies]
sector = ["Technology"]
year = ["2024"]
threat_actor = ["BlackBasta"]

[extra]
severity = "Severe"
data_types = ["Passport", "Health Records"]
attack_vector = "Ransomware"
official_status = "Investigation Closed"
source_url = "https://www.cyberdaily.au/security/10251-zircodata-falls-victim-to-black-basta-ransomware-attack"
archive_link = "https://web.archive.org/web/20240200000000*/https://www.cyberdaily.au/security/10251-zircodata-falls-victim-to-black-basta-ransomware-attack"
affected_parties = ["Monash Health", "Department of Home Affairs", "The Migration Translators"]

[extra.impact]
affected_individuals = 0
individuals_note = "Affected 191 Australian organisations; approximately 4,000 individuals from Monash Health family violence units"
data_volume_gb = 395
record_count = 0
financial_cost_total = 0
ransom_demanded = 0
ransom_paid = 0
estimated_remediation = 0
downtime_hours = 0
downtime_note = ""
+++

## Summary

On 8 February 2024, Victorian data management firm ZircoDATA discovered a network intrusion by the Black Basta ransomware gang that resulted in the encryption of files and exfiltration of approximately 395 gigabytes of sensitive data. The breach affected 191 Australian organisations that used ZircoDATA's document scanning and data management services, including major healthcare providers and government agencies. The compromised data included passport scans, immigration documents, health records from family violence support units dating back to 1970, and confidential government files.

## What Happened

ZircoDATA, a Melbourne-based data management company specializing in document digitization and records management, detected unauthorized network access on 8 February 2024. The Black Basta ransomware group exploited vulnerabilities in ZircoDATA's systems to gain access to client data stored across the company's infrastructure.

On 22 February 2024, Black Basta publicly claimed responsibility for the attack, advertising possession of 395 gigabytes of stolen data on their dark web leak site. The threat actors demonstrated their access by publishing sample documents that included passport scans, immigration identifiers, financial documents, personal user folders, and confidentiality agreements.

The breach compromised historical archived data that ZircoDATA had been contracted to digitize for numerous Australian organizations. The attack particularly impacted sensitive records including:
- Health records from family violence and sexual assault support units (1970-1993) from Monash Health facilities
- Immigration and translation documents from the Department of Home Affairs' Free Translating Service (FTS)
- Government agency records from various departments
- Client documents from approximately 191 Australian organisations

Black Basta is a sophisticated Russian-linked ransomware operation that emerged in 2022 and is known for double extortion tactics—encrypting victim systems while simultaneously stealing data to use as leverage for ransom demands.

The National Office of Cyber Security engaged with ZircoDATA in mid-March 2024 to coordinate response efforts across affected government agencies and organizations. The incident highlighted the systemic risk created when third-party vendors hold sensitive data for numerous clients, creating a single point of failure that can cascade across multiple organizations.

## Impact on Individuals

The breach affected thousands of Australians whose personal information had been entrusted to organizations that contracted ZircoDATA for document management services. The impact was particularly severe for vulnerable populations, including approximately 4,000 individuals who had sought support from family violence and sexual assault units at Monash Medical Centre, Queen Victoria Hospital, and Southern Health facilities between 1970 and 1993.

Compromised information types included:
- **Identity documents**: Passport scans, immigration identifiers, and government-issued identification
- **Health records**: Medical files, treatment records, and support service documentation
- **Financial information**: Financial documents and confidential business records
- **Sensitive personal data**: Records relating to family violence, sexual assault, and other trauma support services

The exposure of decades-old family violence support records created unique risks for victim-survivors, many of whom may have rebuilt their lives assuming these historical records remained confidential. The breach potentially exposed individuals to renewed privacy violations, emotional trauma, and in some cases, risks to physical safety if perpetrators gained access to historical victim location or identity information.

Immigration documents and passport scans exposed through the Home Affairs/Migration Translators data created identity theft risks, as these documents contain comprehensive personal information sufficient for fraudulent identity creation or account takeovers.

The scale of the breach across 191 organizations meant that individuals had no direct relationship with ZircoDATA and may have been unaware that their data had been transferred to a third-party vendor for processing and storage.

## Organisational Response

ZircoDATA publicly acknowledged the breach on 22 February 2024 following Black Basta's leak site posting. The company worked with the National Office of Cyber Security and the National Cyber Security Coordinator to assess the breach scope and coordinate notification to affected client organizations.

Monash Health issued a public statement on 3 May 2024—nearly three months after the initial breach—confirming that approximately 4,000 individuals' historical records from family violence and sexual assault support units had been compromised. The organization offered counseling support and established dedicated communication channels for affected individuals.

In July 2024, ZircoDATA notified the Department of Home Affairs that data from its Free Translating Service subsidiary, The Migration Translators, may have been compromised in the breach. The delayed notification to some affected agencies raised questions about the timeline of ZircoDATA's impact assessment and client notification processes.

The incident demonstrated the complex cascading disclosure requirements when third-party breaches affect numerous client organizations, each of which must conduct its own impact assessment and notification to affected individuals. ZircoDATA did not publicly disclose whether it paid ransom to the Black Basta operators or what specific security remediation measures were implemented following the attack.
