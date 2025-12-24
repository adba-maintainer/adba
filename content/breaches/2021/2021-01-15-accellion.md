+++
title = "Accellion File Transfer Appliance"
date = 2021-01-15
description = "Global supply chain attack on Accellion's legacy file transfer software affected multiple Australian government and healthcare organisations."
draft = false

[taxonomies]
sector = ["Technology"]
year = ["2021"]

[extra]
severity = "Severe"
data_types = ["Email Address", "Driver License", "Physical Address", "Health Records"]
attack_vector = "Third-Party Breach"
official_status = "Remediation Complete"
affected_parties = ["ASIC", "Transport for NSW", "NSW Health", "QIMR Berghofer Medical Research Institute"]
source_url = "https://www.cyber.gov.au/about-us/view-all-content/alerts-and-advisories/accellion-fta-vulnerabilities"
archive_link = "https://web.archive.org/web/20210115/https://www.cyber.gov.au/about-us/view-all-content/alerts-and-advisories/accellion-fta-vulnerabilities"

[extra.impact]
affected_individuals = 0
individuals_note = "Multiple Australian organisations affected with varying data exposure: Transport for NSW confirmed data stolen and published; NSW Health confirmed medical information accessed; ASIC found limited exposure; QIMR Berghofer minimal impact"
+++

## Summary

In late 2020 and early 2021, threat actors exploited multiple zero-day vulnerabilities in Accellion's legacy File Transfer Appliance (FTA) software, affecting approximately 100 organisations worldwide including at least four major Australian entities. The supply chain attack on this widely-used secure file transfer platform gave attackers access to sensitive data held by government agencies, healthcare providers, and other organisations across Australia.

## What Happened

Beginning in December 2020, sophisticated threat actors exploited four zero-day vulnerabilities in Accellion's 20-year-old File Transfer Appliance software. The attackers used SQL injection and web shell techniques to compromise FTA servers globally, accessing files being transferred through the platform.

Accellion's FTA was used by organisations worldwide as a secure file transfer solution for sharing sensitive documents. The vulnerabilities allowed attackers to bypass authentication, execute arbitrary code, and exfiltrate data from servers before organisations became aware of the compromise.

**Australian Organisations Affected:**

1. **ASIC (Australian Securities and Investments Commission)** - Disclosed January 26, 2021
   - Server accessed on December 28, 2020
   - Credit licence application files potentially viewed
   - Forensic investigation found no evidence file contents were accessed

2. **QIMR Berghofer Medical Research Institute** - Disclosed February 11, 2021
   - Queensland medical research institute
   - Minimal data exposure confirmed
   - Limited number of individuals potentially affected

3. **Transport for NSW** - Disclosed February 24, 2021
   - Data confirmed stolen and published on dark web
   - Driver licence details, addresses, contact information exposed
   - Most severe Australian impact with confirmed data theft

4. **NSW Health** - Disclosed June 6, 2021
   - Medical information and patient records accessed
   - Personal and health information of patients and staff compromised
   - Files containing highly sensitive healthcare data

The Australian Cyber Security Centre issued alerts about the Accellion vulnerabilities in January 2021, prompting Australian organisations to assess their exposure.

## Impact on Individuals

Impact varied significantly across affected Australian organisations:

**High Impact (Transport for NSW, NSW Health):**
- Personal data confirmed stolen and in some cases published online
- Medical privacy violations through exposure of patient health records
- Driver licences, addresses, and sensitive personal information compromised
- Ongoing identity theft and fraud risks

**Limited Impact (ASIC, QIMR Berghofer):**
- Forensic investigation found minimal or no confirmed data exfiltration
- Preventative notifications issued to potentially affected individuals

The supply chain nature meant individuals had no direct relationship with Accellion - they had entrusted their data to Australian organisations who used Accellion's software, creating complex notification and remediation challenges.

## Organisational Response

All affected Australian organisations immediately disabled their Accellion FTA systems upon learning of the vulnerabilities. Each organisation:

- Engaged independent cybersecurity experts for forensic investigation
- Worked with the Australian Cyber Security Centre
- Implemented alternative secure file transfer solutions
- Notified affected individuals based on investigation findings

Accellion released patches for the vulnerabilities but urged customers to migrate away from the legacy FTA platform to newer solutions. Many Australian organisations accelerated plans to retire the 20-year-old software.

The incident highlighted the cascading risks of supply chain attacks where a single vendor vulnerability can expose sensitive data across numerous unrelated organisations simultaneously.

## Supply Chain Context

This breach exemplifies supply chain risk in the technology sector. Accellion FTA was trusted by government agencies, healthcare providers, and financial institutions worldwide to securely transfer sensitive files. The compromise of this single platform created a coordinated global data breach affecting organisations that had implemented what they believed to be secure file sharing practices.

The attack demonstrated sophisticated threat actor capabilities to identify and exploit vulnerabilities in widely-deployed enterprise software, creating maximum impact through a single compromise point.
