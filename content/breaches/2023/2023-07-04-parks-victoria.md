+++
title = "Parks Victoria"
date = 2023-07-04
draft = false

[taxonomies]
sector = ["Government"]
year = ["2023"]

[extra]
severity = "Minor"
data_types = ["Email Address", "Phone Number"]
attack_vector = "Misconfiguration"
official_status = "Remediation Complete"
source_url = "https://www.parks.vic.gov.au/"
archive_link = "https://web.archive.org/web/20230704000000*/https://www.parks.vic.gov.au/"

[extra.impact]
affected_individuals = 0
individuals_note = "Very small number of users affected"
data_volume_gb = 0
record_count = 0
financial_cost_total = 0
ransom_demanded = 0
ransom_paid = 0
estimated_remediation = 0
downtime_hours = 0
downtime_note = "Booking system temporarily paused"
+++

## Summary

Parks Victoria experienced a data breach on 4 July 2023 when launching its upgraded online booking system for the 2023/24 camping season. Due to extremely high demand, a technical flaw allowed a small number of users to see other people's booking details in the shopping cart section. The agency apologised and temporarily paused bookings while working with their supplier to fix the issues.

## What Happened

On 4 July 2023, Parks Victoria launched an upgraded online booking system to handle reservations for camping and accommodation, including the highly sought-after Tidal River campground. The system experienced extremely high demand upon opening, which exposed a technical vulnerability.

A configuration issue in the new booking system caused booking information to be incorrectly displayed to other users. When some users added bookings to their cart, they could see personal information and booking details belonging to other customers who were simultaneously using the system.

## Impact on Individuals

A very small number of users were affected by the breach. Those impacted could see other people's booking details, including names, contact information, and reservation details. Parks Victoria's investigation found no evidence that sensitive information such as credit card details were compromised.

The breach was limited to information visible during the booking process and did not involve unauthorised access to Parks Victoria's systems or databases. The issue stemmed from the booking platform's inability to properly handle the extremely high volume of concurrent users.

## Organisational Response

Parks Victoria apologised for the incident and temporarily paused camping and accommodation bookings for the 2023/24 season while addressing the technical issues. The agency worked with their booking system supplier to ensure the platform could properly handle high-demand scenarios and prevent similar data exposure.

Parks Victoria contacted affected individuals to inform them of the breach and the steps being taken to prevent future incidents. The agency emphasised that this was a technical configuration issue rather than a malicious attack.
