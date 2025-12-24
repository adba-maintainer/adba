+++
title = "Court Services Victoria"
date = 2024-01-02
draft = false

[taxonomies]
sector = ["Government"]
year = ["2024"]
threat_actor = ["Qilin"]

[extra]
severity = "Serious"
data_types = []
attack_vector = "Ransomware"
official_status = "Remediation Complete"
source_url = "https://courts.vic.gov.au/news/court-services-victoria-cyber-incident"
archive_link = "https://web.archive.org/web/20240102/courts.vic.gov.au/cyber-incident"
+++

### Summary
Court Services Victoria (CSV), the agency responsible for audio-visual technology in Victorian courts, suffered a Qilin ransomware attack that compromised video and audio recordings of court hearings. Discovered on December 21, 2023, the breach exposed recordings from the Supreme Court, Court of Appeal, County Court, Magistrates' Court, Coroners Court, and Children's Court dating back to November 1, 2023. The incident disrupted court operations and raised serious concerns about the exposure of sensitive legal proceedings.

### What Happened
On December 8, 2023, the Qilin ransomware gang infiltrated Court Services Victoria's audio-visual in-court technology network. The attackers gained unauthorized access to CSV's systems, encrypting data and exfiltrating court hearing recordings before deploying ransomware across the network.

The breach was discovered on December 21, 2023, when multiple CSV staff members were suddenly locked out of their devices. Their screens went black displaying only the message "YOU HAVE BEEN PWND"—a clear indicator of ransomware deployment. This dramatic discovery method suggested the attackers had maintained access for nearly two weeks before activating the ransomware.

The compromised systems contained audio and video recordings of court proceedings, including:
- Supreme Court hearings
- Court of Appeal criminal division proceedings
- County Court hearings
- Committal hearings in the Magistrates' Court
- All Coroners Court hearings
- At least one Children's Court hearing

Cybersecurity expert Robert Potter confirmed evidence pointing to Qilin commercial ransomware, a Russia-linked operation active since July 2022 known for targeting critical infrastructure. While CSV did not officially name the attackers, the Qilin group's involvement was confirmed by multiple cybersecurity sources.

### Impact on Individuals
The breach potentially exposed extraordinarily sensitive information contained in court recordings:

**Criminal proceedings**: Victim testimonies, witness statements, evidence presentations, and accused persons' court appearances

**Civil matters**: Personal disputes, family law proceedings, financial disclosures, and confidential settlements

**Coroners Court**: Death investigation proceedings, often involving grieving families and sensitive medical information

**Children's Court**: Proceedings involving minors, child protection matters, and juvenile justice cases

The exposure of court recordings represents one of the most sensitive types of government data breaches because:
- Legal proceedings often involve highly personal and confidential information
- Victims of crime may have provided testimony under protection orders
- Witnesses may have testified with assurances of security
- Children's identities in youth justice matters are legally protected
- Coronial inquests often involve graphic evidence and grieving families

The breach created risks beyond privacy violations—exposed court recordings could:
- Enable witness intimidation or retaliation
- Compromise ongoing criminal investigations
- Violate suppression orders protecting victims and witnesses
- Expose legally protected information about minors
- Reveal sensitive evidence not intended for public release

The scope of affected individuals is difficult to quantify but potentially includes thousands of parties, witnesses, victims, accused persons, and legal professionals involved in Victorian court proceedings from November 2023 onward.

### Organisational Response
Court Services Victoria immediately notified relevant authorities including Victoria Police, the Victorian Department of Government Services, and the National Identity and Cyber Support Community Service (IDCARE). The organization engaged cybersecurity specialists to investigate the breach, contain the incident, and assess the extent of data exfiltration.

CSV faced significant operational disruption as the ransomware disabled critical audio-visual systems used for recording hearings and facilitating remote/hybrid court appearances. The organization worked systematically to restore services while maintaining security, with video conferencing re-established in most courts by January 16, 2024, and hybrid hearings resuming January 22, 2024.

The incident prompted serious questions about data security in the Victorian court system. The breach highlighted inadequate cybersecurity protections for one of the state's most sensitive government functions. Legal experts and privacy advocates expressed concern about whether CSV had implemented appropriate safeguards for court recordings containing protected information.

CSV implemented enhanced security measures during the recovery period and conducted a comprehensive review of access controls, network segmentation, and monitoring capabilities to prevent similar breaches. The organization did not publicly disclose whether ransom was paid to the Qilin gang or whether exfiltrated court recordings were published on dark web leak sites.

The breach represented a significant cybersecurity incident for Australia's justice system, demonstrating that even core government judicial functions are vulnerable to sophisticated ransomware operations.

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
