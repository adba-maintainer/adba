+++
title = "TissuPath Pathology"
date = 2023-08-24
draft = false

[taxonomies]
sector = ["Health"]
year = ["2023"]

[extra]
severity = "Severe"
data_types = ["Date of Birth", "Physical Address", "Phone Number", "Email Address", "Medicare Number", "Health Records"]
attack_vector = "Third-Party Breach"
official_status = "Remediation Complete"
source_url = "https://www.tissupath.com.au/"
archive_link = "https://web.archive.org/web/20230825000000*/https://www.tissupath.com.au/"

[extra.impact]
affected_individuals = 0
individuals_note = "Patients with referrals from 2011-2020, primarily suspected cancer patients"
data_volume_gb = 446
record_count = 735414
financial_cost_total = 0
ransom_demanded = 0
ransom_paid = 0
estimated_remediation = 0
downtime_hours = 0
downtime_note = ""

[extra.threat_actor]
name = "ALPHV (BlackCat)"
+++

### Summary

TissuPath Pathology, a Melbourne-based specialist pathology firm, disclosed on 24 August 2023 that it had experienced a cyber security incident in which the ALPHV (BlackCat) ransomware gang gained access to detailed patient records by exploiting third-party supplier login credentials. The attack resulted in the exfiltration of 446 gigabytes containing 735,414 files—patient request forms from 2011 to 2020, primarily for suspected cancer patients. The threat actor contacted TissuPath on 24 August threatening to publish patient information within 48 hours if no payment was made.

### What Happened

Core Desktop, a Victorian IT company that provided services to TissuPath, discovered a breach on 22 August 2023. The ALPHV (BlackCat) ransomware gang had gained initial access via Core Desktop's systems through a vulnerability in their remote access toolkit (RAT). Through this third-party compromise, the attackers accessed TissuPath's backup storage drive containing patient pathology records.

On 24 August 2023, the threat actor contacted TissuPath threatening to publish patient information within 48 hours if no ransom was paid. TissuPath released a public statement the same day notifying patients of the breach. The storage drive accessed contained records specific to pathology referrals for suspected cancer patients from 2011 to 2020, totalling 471 gigabytes of information.

The attackers ultimately exfiltrated 446 gigabytes and 735,414 files. Sample files released on the dark web included prostate scans, doctor referrals, doctors' meeting notes, patient names and addresses, and individual diagnoses of breast and testicular cancer, and even liver biopsies.

### Impact on Individuals

The breach exposed highly sensitive medical information for patients who had pathology referrals between 2011 and 2020, with a focus on suspected cancer patients. The compromised data included:

- Patient names, dates of birth, contact details
- Medicare numbers
- Private health insurance details
- Detailed medical records including cancer diagnoses
- Pathology test results and referral notes
- Doctor communications and meeting notes

The exposure of cancer diagnoses and detailed pathology records represents one of the most sensitive types of health data breaches possible. Cancer patients and those who underwent testing for suspected cancer face not only privacy violations but potential psychological harm from knowing their intimate health struggles are on the dark web. The decade-long span of records means many affected individuals may have moved on from that difficult period of their lives, making the re-traumatisation particularly acute.

The scale of the breach—over 735,000 files covering 10 years of patient records—makes it one of the most significant health data breaches in Australian history.

### Organisational Response

TissuPath notified the Office of the Australian Information Commissioner of an eligible data breach and began the complex task of analysing the data shared on the dark web with assistance from cyber security specialists.

The firm worked to identify and contact affected patients, though the sheer volume of files and the 10-year span of records created significant challenges in notification. The incident raised concerns about delayed notification, with some affected individuals expressing frustration about the timing of being informed.

TissuPath emphasised that the breach occurred through their third-party IT supplier rather than their own systems, though this did not reduce the severity of the impact on patients. The incident highlighted the critical importance of vendor security in healthcare settings and the risks posed by third-party access to sensitive medical records, even when stored on backup systems.
