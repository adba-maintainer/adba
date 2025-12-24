+++
title = "Ambulance Tasmania"
date = 2021-01-08
description = "Unencrypted pager network exposed patient medical data including HIV status for three months."
draft = false

[taxonomies]
sector = ["Health"]
year = ["2021"]

[extra]
severity = "Serious"
data_types = ["Health Records", "Physical Address", "Date of Birth"]
attack_vector = "Misconfiguration"
official_status = "Remediation Complete"
source_url = "https://www.abc.net.au/news/2021-01-08/tasmania-ambulance-patient-privacy-breach/13040278"
archive_link = "https://web.archive.org/web/20210108/https://www.abc.net.au/news/2021-01-08/tasmania-ambulance-patient-privacy-breach/13040278"

[extra.impact]
affected_individuals = 0
individuals_note = "All patients who called ambulances between November 2020 and mid-January 2021"
+++

## Summary

Ambulance Tasmania exposed sensitive patient medical data through its unencrypted pager network between November 2020 and January 2021. Personal details of every patient who called an ambulance during this period were intercepted and published online, including a patient's HIV status, medical conditions, and emergency incident addresses.

## What Happened

Ambulance Tasmania used an outdated alphanumeric pager network that transmitted messages in plain text without encryption. Radio data from the pager network was intercepted using readily available equipment and converted to text before being published online.

The pager messages contained highly sensitive information about ambulance call-outs, including patient medical conditions, locations, ages, and in at least one case, a patient's HIV status. The unencrypted transmissions were accessible to anyone with basic radio equipment costing under $30.

## Impact on Individuals

The exposure of unencrypted pager data revealed highly sensitive health information:

- **Medical privacy violated**: HIV status, mental health conditions, overdoses, and other diagnoses exposed
- **Location data**: Home addresses linked to medical emergencies
- **Stigmatisation risk**: Public exposure of sensitive health conditions could lead to discrimination

## Organisational Response

Following public disclosure of the breach, cybersecurity experts called for the replacement of outdated pager technology. Tasmania Police referred the matter for investigation. The incident highlighted the risks of using legacy, unencrypted communication systems for transmitting sensitive health information in emergency services.
