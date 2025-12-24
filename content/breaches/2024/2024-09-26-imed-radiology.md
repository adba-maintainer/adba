+++
title = "I-MED Radiology"
date = 2024-09-26
draft = false

[taxonomies]
sector = ["Health"]
year = ["2024"]

[extra]
severity = "Serious"
data_types = ["Date of Birth", "Health Records", "Physical Address"]
attack_vector = "Phishing"
official_status = "Remediation Complete"
source_url = "https://www.crikey.com.au/2024/09/26/i-med-data-breach-patient-files-exposed/"
archive_link = "https://web.archive.org/web/20240926/crikey.com.au/i-med-data-breach"
+++

### Summary
Australia's largest medical imaging provider I-MED Radiology suffered a data breach when login credentials for three healthcare professional accounts were compromised and used to access tens of thousands of patient records. The credentials had been publicly available online for an extended period before the breach was discovered in September 2024, allowing unauthorized access to patient information dating back to 2006.

### What Happened
The breach occurred through credential compromise, likely via Infostealer malware embedded in browsers on devices used by healthcare professionals. An unauthorized party obtained login credentials for three accounts—one associated with St Vincent's Public Hospital, a cancer clinic in Sydney's south-west, and an Australian radiologist—and used them to access I-MED's online referrer portal.

These compromised credentials had been publicly available online for a significant period before I-MED discovered the unauthorized access. The attacker gained access to I-MED's radiology patient portal, which contained extensive patient information spanning nearly two decades. An anonymous source contacted media outlets in September 2024, providing evidence of the breach including screenshots showing patient data.

### Impact on Individuals
The breach exposed sensitive medical imaging information including:
- Full names and dates of birth
- Gender and residential addresses
- Types of scans received and examination dates
- Radiology scan images
- Clinical notes from radiologists
- Referring physician details
- Medical history dating back to 2006

The long-term nature of the accessible data is particularly concerning, as records going back to 2006 suggest tens of thousands of patients may have been affected. Medical imaging data reveals intimate health information and could be used to discriminate against individuals or cause psychological harm if disclosed.

The exposure of nearly two decades of patient records creates ongoing risks for affected individuals, as this health information cannot be changed and remains sensitive indefinitely.

### Organisational Response
Upon learning of the credential compromise, I-MED immediately suspended the affected accounts and contacted the account holders to enforce password resets. The company notified the Office of the Australian Information Commissioner (OAIC), the National Office of Cyber Security, and the Australian Signals Directorate.

I-MED implemented additional security measures to prevent similar incidents and worked with authorities to investigate the scope of the breach. The company emphasized that the breach resulted from compromised healthcare professional credentials rather than a direct attack on I-MED's systems.

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
