+++
title = "Ticketmaster Australia"
date = 2018-06-23
draft = false

[taxonomies]
sector = ["Retail", "Technology"]
year = ["2018"]

[extra]
severity = "Serious"
data_types = ["Credit Card", "Email Address", "Phone Number", "Physical Address"]
attack_vector = "Third-Party Breach"
official_status = "Investigation Closed"
source_url = "https://www.ticketmaster.com.au/h/customer-support.html"
archive_link = "https://web.archive.org/web/20180623000000*/ticketmaster.com.au"

[extra.impact]
affected_individuals = 0
individuals_note = "Australian customers who purchased tickets between February and June 2018, exact numbers not disclosed"
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

Ticketmaster Australia disclosed in June 2018 that customer payment details may have been stolen through a compromised third-party customer support product. The breach, which affected Ticketmaster operations globally including Australia, exposed credit card information and personal details of customers who purchased tickets between February and June 2018. The incident was caused by malicious code injected into a third-party chat software used on Ticketmaster's website.

## What Happened

Attackers compromised a third-party customer support chat application used on Ticketmaster's website. The compromised software, provided by a company called Inbenta Technologies, was injected with malicious code that captured customer payment information as it was entered during the ticket purchasing process.

Between February and June 2018, when customers entered their credit card details to purchase tickets on Ticketmaster's website, the malicious code copied this information and sent it to the attackers. The breach went undetected for approximately four months, during which time an unknown number of transactions were compromised.

Ticketmaster discovered the breach in June 2018 after being alerted by a third party about suspicious activity. The company immediately removed the compromised chat application and launched an investigation. The breach was a supply chain attack, where attackers targeted a vendor's software to gain access to data from the vendor's customers—in this case, Ticketmaster and its ticket buyers.

## Impact on Individuals

Australian customers who purchased tickets through Ticketmaster's website between February and June 2018 were potentially affected. The compromised information included:

- **Credit card details**: Card numbers, expiry dates, and CVV codes
- **Personal information**: Names, email addresses, phone numbers, and billing addresses
- **Transaction data**: Purchase history and ticket details

Risks to affected individuals:

- **Financial fraud**: Credit card information could be used for unauthorised purchases
- **Identity theft**: Combination of payment and personal information could enable broader fraud
- **Phishing attacks**: Email addresses and knowledge of ticket purchases could be used for targeted scams
- **Ongoing monitoring burden**: Need to monitor bank statements and credit reports

Because the breach involved complete credit card details including CVV codes, there was an elevated risk of immediate fraudulent transactions, requiring affected individuals to closely monitor their accounts and potentially cancel and replace their cards.

## Organisational Response

Ticketmaster responded to the breach by:
- Immediately removing the compromised third-party chat software
- Notifying potentially affected customers via email
- Recommending that affected customers contact their banks to monitor for fraudulent activity
- Working with payment card companies to flag potentially compromised cards
- Engaging cybersecurity experts to investigate the full extent of the breach
- Reporting the incident to relevant data protection authorities and law enforcement
- Reviewing security of all third-party software and services

The company apologised to affected customers and emphasised that the breach was caused by a compromised third-party vendor rather than Ticketmaster's own systems, though this distinction offered little comfort to affected customers whose payment details were stolen.

## Supply Chain Security Implications

The Ticketmaster breach exemplified the risks of third-party software in modern web applications:

- **Trust in vendors**: Organisations must trust that third-party software providers maintain strong security
- **Code injection risks**: Third-party scripts running on websites can be compromised to capture sensitive data
- **Detection challenges**: Malicious code in third-party components can be difficult to detect
- **Shared responsibility**: While the breach originated with a vendor, Ticketmaster bore responsibility for customer impact
- **Vendor vetting**: Highlighted need for rigorous security assessment of third-party providers

The incident occurred during a broader wave of "web skimming" or "formjacking" attacks, where attackers inject malicious code into e-commerce websites to steal payment information. These attacks often target third-party components because a single successful compromise can affect multiple websites using the same software.

## Payment Card Industry Response

The breach prompted action from payment card companies and the payment card industry:
- Banks flagged potentially compromised cards and contacted customers
- Some financial institutions proactively reissued cards to affected customers
- Payment card networks enhanced fraud monitoring for Ticketmaster transactions
- Industry discussion about security requirements for third-party scripts on payment pages

## Long-term Impact

The Ticketmaster breach contributed to:
- Greater scrutiny of third-party scripts and software on e-commerce websites
- Enhanced security requirements for customer support and chat applications
- Industry-wide recognition of supply chain cybersecurity risks
- Regulatory focus on organisations' responsibility for third-party vendor security
- Consumer awareness about the risks of saving payment information on ticketing platforms

The incident remains a significant example of supply chain cybersecurity risk and the challenges of securing modern web applications that rely on numerous third-party components.
