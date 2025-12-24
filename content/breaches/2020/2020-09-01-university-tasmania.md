+++
title = "University of Tasmania"
date = 2020-09-01
draft = false

[taxonomies]
sector = ["Education"]
year = ["2020"]

[extra]
severity = "Minor"
data_types = ["Email Address", "Phone Number"]
attack_vector = "Misconfiguration"
official_status = "Remediation Complete"
source_url = "https://www.itnews.com.au/news/utas-contacts-19900-students-caught-up-in-data-breach-552631"
archive_link = "https://web.archive.org/web/20200901/https://www.itnews.com.au/"

[extra.impact]
affected_individuals = 19900
individuals_note = ""
data_volume_gb = 0
record_count = 19900
financial_cost_total = 0
ransom_demanded = 0
ransom_paid = 0
estimated_remediation = 0
downtime_hours = 0
downtime_note = ""
+++

The University of Tasmania exposed personal data of 19,900 students through a SharePoint misconfiguration that gave anyone with a UTAS email address access to student records.

### What Happened

A misconfiguration in the University of Tasmania's SharePoint system resulted in student records being accessible to anyone with a UTAS email address. Instead of being restricted to authorised staff, a SharePoint site containing student information was visible to all UTAS email account holders, including other students and general staff.

The exposed data included student names, email addresses, student identification numbers, and phone numbers. The breach was an internal exposure rather than a public internet leak, but still represented a significant privacy violation as students could access each other's information.

### Impact on Individuals

While the data exposure was limited to the university community rather than the public internet, affected students still faced privacy violations. The exposure of student contact details and ID numbers could enable harassment, phishing targeting university students, or misuse of student identities within the university system.

### Organisational Response

UTAS identified and corrected the misconfiguration promptly once discovered. The university notified all 19,900 affected students and reported the breach to the OAIC. The incident highlighted the importance of proper access controls in cloud-based collaboration platforms and the risks of misconfigured SharePoint permissions.
