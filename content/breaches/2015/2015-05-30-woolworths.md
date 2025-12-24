+++
title = "Woolworths"
date = 2015-05-30
description = "Woolworths accidentally emailed a spreadsheet containing gift card details for 8,000 vouchers worth $1.3 million to over 1,000 customers, forcing the cancellation of all affected cards."
draft = false

[taxonomies]
sector = ["Retail"]
year = ["2015"]

[extra]
severity = "Minor"
data_types = ["Email Address"]
attack_vector = "Human Error"
official_status = "Remediation Complete"
source_url = "https://www.lifehacker.com.au/2015/05/voucher-codes-personal-details-exposed-in-woolworths-accidental-mass-email/"
archive_link = "https://web.archive.org/web/20240000000000*/https://www.lifehacker.com.au/2015/05/voucher-codes-personal-details-exposed-in-woolworths-accidental-mass-email/"

[extra.impact]
affected_individuals = 7941
individuals_note = "Customers who purchased Groupon gift vouchers had their details and voucher codes exposed"
data_volume_gb = 0
record_count = 7941
financial_cost_total = 1308505
ransom_demanded = 0
ransom_paid = 0
estimated_remediation = 1308505
downtime_hours = 0
downtime_note = "All vouchers worth $1.3 million were cancelled and reissued"
+++

## Summary

On 30 May 2015, Australian supermarket chain Woolworths accidentally sent an email to over 1,000 customers containing an Excel spreadsheet with the names, email addresses, and redeemable voucher codes for 7,941 gift cards worth approximately $1.3 million. The error occurred during a promotional campaign for gift vouchers purchased through Groupon, forcing Woolworths to immediately cancel all affected vouchers and reissue new ones to legitimate customers.

## What Happened

Woolworths was distributing electronic gift vouchers to customers who had purchased them through a Groupon promotion. On Saturday morning, 30 May 2015, the company sent confirmation emails to customers, but made a critical error by attaching a spreadsheet containing the complete list of all voucher details.

The spreadsheet included customer names, email addresses, and most critically, the card numbers, expiration dates, and values of 7,941 gift cards. This meant that anyone who received the email could potentially redeem vouchers belonging to other customers before the legitimate purchasers had a chance to use them.

The breach was discovered quickly when customers began reporting that their vouchers had already been spent when they attempted to use them. Some recipients of the errant email had already accessed and used other people's gift vouchers before Woolworths could respond.

## Impact on Individuals

The breach exposed customer names and email addresses to over 1,000 recipients, though notably no credit card or other financial information was included in the leaked spreadsheet. The primary impact was the compromise of gift voucher codes, allowing unauthorized individuals to redeem vouchers belonging to others.

Customers who attempted to use their legitimate vouchers on Saturday discovered they had already been spent, causing frustration and inconvenience. The total value of compromised vouchers was $1,308,505, requiring all affected customers to wait for replacement vouchers to be issued.

While the personal information exposure was relatively limited (names and emails only), the incident demonstrated how simple administrative errors can have significant financial and customer service impacts.

## Organisational Response

Woolworths acted swiftly once the breach was discovered on Saturday morning. By Saturday evening, the company had:

1. Cancelled all 7,941 affected vouchers worth $1,308,505
2. Sent notification emails to all affected customers explaining the situation
3. Committed to issuing replacement gift cards to all legitimate purchasers
4. Apologised publicly for the data leak

A Woolworths spokesperson stated: "We sincerely apologise to our customers for this error and any inconvenience caused." The company took full responsibility for the administrative error and covered the entire cost of reissuing the vouchers.

The incident highlighted the risks of bulk email campaigns containing sensitive information and the importance of proper verification procedures before sending mass communications with attached spreadsheets.
