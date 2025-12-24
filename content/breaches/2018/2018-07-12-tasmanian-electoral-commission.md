+++
title = "Tasmanian Electoral Commission"
date = 2018-07-12
draft = false

[taxonomies]
sector = ["Government"]
year = ["2018"]

[extra]
severity = "Serious"
data_types = ["Email Address", "Phone Number", "Physical Address", "Date of Birth", "Driver License"]
attack_vector = "Third-Party Breach"
official_status = "Investigation Closed"
source_url = "https://www.tec.tas.gov.au/news/data-breach-notification"
archive_link = "https://web.archive.org/web/20180712000000*/tec.tas.gov.au"

[extra.impact]
affected_individuals = 0
individuals_note = "Tasmanian voters who applied for ExpressVote service, exact numbers not disclosed"
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

The Tasmanian Electoral Commission (TEC) disclosed a data breach in July 2018 affecting voters who had applied for the ExpressVote telephone voting service. The breach occurred through Typeform, a third-party online form platform used by the TEC to collect voter applications. Personal information including driver's licence numbers, dates of birth, and contact details were potentially accessed by attackers who compromised Typeform's systems.

## What Happened

The breach originated with Typeform, an international online form and survey platform used by the Tasmanian Electoral Commission to collect applications for its ExpressVote service. ExpressVote allows eligible voters (such as those with disabilities or living remotely) to cast their votes via telephone.

In late June 2018, attackers breached Typeform's systems and accessed data from forms created by Typeform's customers, including the TEC's voter application forms. The compromised information included sensitive identity documents that voters had submitted to verify their eligibility for telephone voting.

Typeform notified the TEC of the breach in early July, and the TEC subsequently notified affected voters. The breach highlighted the risks government agencies face when using third-party cloud platforms to collect sensitive citizen information.

## Impact on Individuals

Tasmanian voters who applied for ExpressVote service were affected. The compromised information included:

- **Identity documents**: Driver's licence numbers
- **Personal details**: Names, dates of birth, addresses
- **Contact information**: Email addresses and phone numbers
- **Electoral information**: Details about voting eligibility and needs

Risks to affected individuals:

- **Identity theft**: Driver's licence numbers combined with dates of birth and addresses create significant identity fraud risk
- **Targeted phishing**: Attackers knowing individuals had specific voting needs could craft convincing scams
- **Electoral fraud**: Potential for identity information to be misused in electoral contexts
- **Privacy violation**: Disclosure of information about voters' circumstances (disability, remote location)

The involvement of government identity documents made this breach more serious than typical marketing form breaches. Driver's licence numbers are a key component of identity verification in Australia and their compromise creates lasting risk.

## Organisational Response

The Tasmanian Electoral Commission responded by:
- Notifying affected voters as soon as TEC was informed by Typeform
- Advising voters to monitor for suspicious activity and identity theft
- Reviewing use of third-party platforms for collecting sensitive information
- Reporting the incident to relevant authorities
- Providing guidance to affected individuals on protecting their identity

TEC emphasised that the breach occurred in Typeform's systems, not the TEC's own systems, though the Commission acknowledged responsibility for protecting voter data regardless of where it was stored.

## Third-Party Platform Risks

The breach was part of a broader Typeform incident that affected multiple Australian organisations in July 2018, including:
- Bakers Delight
- Airtasker
- Townsville City Council
- Cairns Regional Council

The widespread impact highlighted systemic risks with cloud form platforms:

- **Data aggregation**: Platforms holding data from many organisations create high-value targets
- **Cascading breaches**: Single platform breach affects multiple organisations simultaneously
- **Government data sensitivity**: Use of commercial platforms for collecting government identity documents
- **Vendor security dependency**: Organisations' data security depends on third-party security practices
- **Notification complexity**: Platform providers, not data controllers, discovering breaches first

## Electoral System Security Implications

The breach raised important questions about electoral system cybersecurity:

- **Voter data protection**: Security of systems used to administer elections
- **Third-party dependencies**: Risks of using commercial platforms for electoral processes
- **Voter confidence**: Impact of breaches on public trust in electoral systems
- **Accessibility vs security**: Balancing accessible voting options with data protection

While the breach did not directly affect the voting process itself, it exposed personal information of voters who required alternative voting arrangements, highlighting vulnerabilities in electoral administration systems.

## Government Cloud Services

The incident contributed to broader policy discussions about government use of cloud platforms:
- Enhanced scrutiny of third-party platforms used by government agencies
- Development of stricter requirements for vendors handling government data
- Increased emphasis on data sovereignty and Australian-hosted solutions
- Recognition that convenience of cloud platforms must be balanced with security

The breach occurred during a period of growing government adoption of cloud services, prompting review of security requirements and vendor assessment processes for platforms handling sensitive citizen data.

## Long-term Impact

The Tasmanian Electoral Commission breach had lasting effects:
- Greater caution in government use of international cloud platforms for sensitive data
- Enhanced vendor security requirements in government procurement
- Increased awareness of supply chain risks in electoral administration
- Stronger protocols for assessing third-party platforms before collecting citizen data

The incident remains relevant in discussions about balancing digital convenience with data security in government services, particularly for electoral systems where public trust is paramount.
