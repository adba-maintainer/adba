+++
title = "Airtasker"
date = 2018-07-03
draft = false

[taxonomies]
sector = ["Technology"]
year = ["2018"]

[extra]
severity = "Minor"
data_types = ["Email Address", "Phone Number"]
attack_vector = "Third-Party Breach"
official_status = "Investigation Closed"
source_url = "https://www.airtasker.com/blog/typeform-data-breach-notification/"
archive_link = "https://web.archive.org/web/20180703000000*/airtasker.com"

[extra.impact]
affected_individuals = 0
individuals_note = "Small number of Airtasker users who completed surveys via Typeform"
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

Airtasker, an Australian online marketplace for local services and tasks, disclosed in July 2018 that a small amount of user data may have been compromised through the Typeform breach. Airtasker had used Typeform to collect user feedback and conduct surveys, and when Typeform's systems were hacked, some Airtasker user information was potentially accessed. The company was transparent about the limited scope and low risk of the incident.

## What Happened

In late June 2018, attackers breached Typeform, a third-party online survey and form platform used by Airtasker to collect user feedback. The breach gave attackers potential access to data collected through forms Airtasker had created using Typeform's service.

Airtasker had used Typeform for user research, surveys, and feedback collection. The compromised information was limited to what users had voluntarily provided in these surveys, primarily email addresses and phone numbers. Importantly, the breach did not affect Airtasker's main platform systems, user accounts, task data, or payment information.

Typeform notified Airtasker of the breach in early July 2018, and Airtasker quickly assessed the impact and notified potentially affected users. The company emphasised that only a small number of users who had completed specific surveys were affected.

## Impact on Individuals

The impact was minimal for the small number of affected users:

- **Limited data**: Only email addresses and phone numbers from survey responses
- **No account compromise**: Airtasker platform accounts were not affected
- **No financial data**: No payment information or financial details compromised
- **Small scale**: Only users who had completed specific Typeform surveys were affected
- **Voluntary disclosure**: Information users had chosen to provide in feedback surveys

Potential risks were limited to:
- Spam or unwanted communications to exposed contact details
- Minor privacy concern from disclosure of survey participation
- Potential phishing attempts using knowledge of Airtasker usage

## Organisational Response

Airtasker demonstrated good transparency and communication:
- Promptly notified potentially affected users after being informed by Typeform
- Clearly explained the limited scope of the breach
- Emphasised that Airtasker's main platform was not compromised
- Specified that the breach involved a third-party service, not Airtasker's systems
- Provided clear guidance on what was and was not affected
- Advised users to be cautious of suspicious communications

The company's blog post notification was clear, factual, and appropriately reassuring while still taking the incident seriously.

## Typeform Supply Chain Incident

Airtasker was one of several Australian organisations affected by the July 2018 Typeform breach:
- Tasmanian Electoral Commission (voter applications)
- Bakers Delight (competition entries)
- Townsville City Council (public surveys)
- Cairns Regional Council (feedback forms)

The coordinated impact on multiple organisations demonstrated the supply chain nature of the breach, where a single platform compromise affected many customers simultaneously.

## Platform Technology Context

The incident highlighted considerations for technology platforms using third-party services:

- **Limited integration**: Airtasker's limited use of Typeform (only for surveys) minimised exposure
- **Data segregation**: Core platform data was separate from survey/feedback systems
- **Vendor transparency**: Importance of vendors quickly notifying customers of breaches
- **User communication**: Need for clear explanation of what was and wasn't affected

Airtasker's architecture, which kept survey data separate from core platform operations, limited the breach impact significantly.

## Third-Party Service Risks

The breach demonstrated typical risks of using cloud services:

- **Dependency on vendor security**: Organisations rely on third-party security practices
- **Data held externally**: Information collected via external platforms is outside direct control
- **Breach notification timing**: Organisations learn of breaches from vendors, not through own monitoring
- **Limited remediation options**: Can only respond, not prevent, vendor breaches

## User Research and Feedback Collection

The incident raised questions about data collection for user research:

- **Platform selection**: Evaluating security of tools used for user feedback
- **Data minimisation**: Collecting only necessary information in surveys
- **Alternative methods**: Considering in-house solutions for sensitive user research
- **User expectations**: Whether survey participants expect high security for feedback data

## Comparison to Core Platform Breach

Airtasker's communication effectively distinguished this third-party breach from a core platform compromise:

- ✅ Typeform surveys affected
- ✅ Limited to specific survey participants
- ✅ Only contact information
- ❌ Airtasker platform NOT compromised
- ❌ User accounts NOT affected
- ❌ Task data NOT accessed
- ❌ Payment information NOT compromised

This clear delineation helped users understand the limited scope and low risk of the incident.

## Long-term Impact

The Airtasker Typeform incident contributed to:
- Enhanced assessment of third-party services for user research
- Recognition of the importance of data segregation (survey vs core platform data)
- Best practices for communicating about third-party breaches
- Understanding that transparent communication about limited breaches can maintain user trust

The incident demonstrated how technology companies can handle third-party breaches responsibly through clear communication and appropriate scoping of the impact, helping maintain user confidence despite the security incident.
