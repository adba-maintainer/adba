+++
title = "Transport for NSW"
date = 2020-08-01
draft = false

[taxonomies]
sector = ["Government"]
year = ["2020"]

[extra]
severity = "Serious"
data_types = ["Driver License", "Physical Address", "Date of Birth"]
attack_vector = "Misconfiguration"
official_status = "Remediation Complete"
source_url = "https://www.itnews.com.au/news/over-54000-scanned-nsw-drivers-licences-found-in-open-cloud-storage-551123"
archive_link = "https://web.archive.org/web/20200801/https://www.itnews.com.au/"

[extra.impact]
affected_individuals = 54000
individuals_note = ""
data_volume_gb = 0
record_count = 54000
financial_cost_total = 0
ransom_demanded = 0
ransom_paid = 0
estimated_remediation = 0
downtime_hours = 0
downtime_note = ""
+++

Over 54,000 scanned NSW driver's licences were discovered in an unsecured AWS S3 cloud storage bucket, though the source and responsible party remained unclear for months, with affected individuals not contacted for over four months.

### What Happened

Security researcher Bob Diachenko discovered an open AWS S3 storage bucket containing scanned images of 54,175 NSW driver's licences. The bucket was publicly accessible without authentication, meaning anyone with the URL could view and download the licence images.

The scanned licences included full names, addresses, dates of birth, licence numbers, and photographs—all the information needed for identity theft. The origin of the data remained mysterious, with suggestions it may have come from a fleet management company, toll road operator, or other entity that collected licence scans for verification purposes.

Critically, Transport for NSW and Service NSW took over four months to begin notifying affected individuals, despite the severity of the exposure.

### Impact on Individuals

The exposure of driver's licence scans created severe identity theft risks. NSW driver's licences are a primary form of identification in Australia, accepted for opening bank accounts, applying for credit, and accessing government services. Victims faced risks of fraudulent identity document creation and identity crime.

### Organisational Response

The response was criticised as inadequate, with significant delays in notification and unclear accountability. The incident raised questions about third-party data handling practices and the lack of visibility government agencies have over where citizens' identity documents end up. The delayed notification meant affected individuals were unaware of their risk exposure for an extended period.
