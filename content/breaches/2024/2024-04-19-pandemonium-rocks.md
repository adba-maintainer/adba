+++
title = "Pandemonium Rocks Music Festival"
date = 2024-04-19
draft = false

[taxonomies]
sector = ["Accommodation & Hospitality"]
year = ["2024"]

[extra]
severity = "Minor"
data_types = ["Bank Account Number", "Email Address", "Phone Number"]
attack_vector = "Misconfiguration"
official_status = "Remediation Complete"
source_url = "https://tonedeaf.thebrag.com/massive-data-breach-as-pandemonium-rocks-exposes-hundreds-of-bank-accounts/"
archive_link = "https://web.archive.org/web/20240419/tonedeaf.thebrag.com/pandemonium-rocks-breach"
+++

### Summary
Pandemonium Rocks music festival exposed personal and banking information of over 400 ticketholders on April 19, 2024 when an admin tab was accidentally left enabled on a refund request form. The breach occurred during a tumultuous period for the festival after 7 of 13 scheduled bands canceled, prompting attendees to request partial refunds. The exposed data—visible for just 7 minutes between 7:13pm and 7:20pm—included names, bank account details (BSB and account numbers), email addresses, and phone numbers.

### What Happened
Pandemonium Rocks, a rock music festival, experienced dramatic lineup changes when 7 out of 13 scheduled bands dropped out shortly before the event. In response, festival organizers set up an online refund form allowing ticketholders to claim partial refunds for the diminished lineup.

On Friday evening, April 19, 2024, someone accidentally left the admin tab enabled on the refund form hosted on the festival's website. This configuration error meant that anyone accessing the form could view a results tab displaying personal and financial information from all previous refund applicants.

The timeline of the exposure:
- 7:13pm: Festival organizers were alerted to the data exposure
- 7:20pm: The admin tab was disabled, closing the vulnerability
- **Total exposure window: 7 minutes**

During this brief period, the form displayed:
- Full names of refund applicants
- Bank account numbers and BSB (Bank-State-Branch) codes
- Email addresses
- Phone numbers

The breach resulted from human error during what was already a stressful period for festival organizers dealing with major lineup cancellations and the logistical challenges of processing hundreds of refund requests.

### Impact on Individuals
The breach affected over 400 ticketholders who had submitted refund requests following the festival's lineup collapse. The exposed information included highly sensitive financial data:

**Bank account details (BSB and account numbers)**: This combination allows direct deposits and, in some circumstances, direct debit setup. While Australian banking systems have protections against unauthorized debits, the exposure creates risks for:
- Fraudulent direct debit attempts
- Social engineering attacks using knowledge of banking details
- Account verification fraud
- Potential money laundering schemes using compromised account numbers

**Contact information (email, phone)**: Combined with names and the context of festival attendance, this enables:
- Targeted phishing impersonating the festival or refund processing
- Spam and unwanted marketing
- Identity theft preparation when combined with other data sources

**Context exposure**: Knowledge that individuals attended (or planned to attend) a specific music festival and were seeking refunds reveals:
- Financial behavior and circumstances
- Music preferences and lifestyle
- Potential vulnerability to festival-related scams

The 7-minute exposure window was remarkably brief, potentially limiting the number of malicious actors who discovered and exploited the exposed data. However, even a short exposure is sufficient for automated scraping tools or anyone specifically monitoring the refund form during that window.

Affected individuals were advised to:
- Contact their banks to update account information or add monitoring
- Be alert for suspicious emails or texts referencing the festival or refunds
- Monitor bank accounts for unauthorized transactions
- Report any suspicious activity to authorities

### Organisational Response
Pandemonium Rocks responded quickly once alerted to the data exposure at 7:13pm, disabling the admin tab within 7 minutes by 7:20pm. This rapid response limited the exposure window, though any public data exposure is serious.

**Immediate actions:**
- Disabled the admin tab at 7:20pm, closing the vulnerability
- Began assessing which individuals' data was exposed
- Prepared to contact all affected refund applicants

**Notification:**
Festival organizers committed to directly contacting all individuals who filled out the form during the exposure timeframe. The organization advised affected ticketholders to:
- Contact their banks to update account information
- Monitor accounts for suspicious activity
- Be vigilant for potential fraud attempts

**Context of crisis:**
The data breach compounded an already troubled event. The festival had suffered:
- Cancellation of 7 out of 13 headlining acts
- Significant attendee dissatisfaction and refund demands
- Reputational damage from the lineup collapse
- Logistical challenges of processing hundreds of refund requests

The breach occurred while organizers were managing this crisis, suggesting inadequate security review of hastily implemented refund processes. The use of a web form with an admin tab that could be accidentally left enabled indicates:
- Lack of proper access controls separating admin and public interfaces
- Insufficient testing before deploying the refund form
- Possible use of basic form tools not designed for handling sensitive financial data
- Absence of security review during crisis response

The incident highlighted risks when organizations rapidly deploy systems to handle crisis situations without adequate security consideration. While the organizers' 7-minute response time was commendable, the breach should not have occurred at all given the sensitivity of banking information being collected.

The troubled Pandemonium Rocks festival ultimately became a cautionary tale about both event management and data security, with the breach representing an unfortunate additional blow to an already struggling event.

[extra.impact]
affected_individuals = 400
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
