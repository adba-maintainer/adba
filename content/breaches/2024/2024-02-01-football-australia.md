+++
title = "Football Australia"
date = 2024-02-01
draft = false

[taxonomies]
sector = ["Non-Profit"]
year = ["2024"]

[extra]
severity = "Serious"
data_types = ["Passport", "Email Address", "Phone Number", "Physical Address"]
attack_vector = "Misconfiguration"
official_status = "Remediation Complete"
source_url = "https://www.cyberdaily.au/security/10113-personal-data-exposed-in-football-australia-data-leak-after-database-left-accesible"
archive_link = "https://web.archive.org/web/20240201/cyberdaily.au/football-australia-data-leak"
+++

### Summary
Football Australia, the governing body for soccer in Australia, exposed sensitive personal information of approximately 1,600 A-League players, team personnel, ticket buyers, and family members for 681 days due to AWS access keys hardcoded into a webpage's HTML. Discovered by Cybernews researchers in early February 2024, the misconfiguration allowed public access to 127 Amazon Web Services data buckets containing passport details, player contracts, and personal documents spanning April 2022 to February 2024.

### What Happened
Football Australia inadvertently hardcoded Amazon Web Services (AWS) access keys directly into the HTML source code of a subdomain webpage, making these credentials publicly visible to anyone who viewed the page source. This critical security misconfiguration resulted from human error during website development or maintenance.

The exposed AWS keys granted access to 127 data storage buckets containing:
- A-League Women, A-League Men, and A-League Youth player information
- Player contracts and employment documents
- Passport scans and identity documents
- Team personnel records
- Family member information for some players
- Ticket purchaser personal data

The Cybernews research team discovered the exposed keys in early February 2024 and responsibly disclosed the vulnerability to Football Australia. The organization had unknowingly left this data publicly accessible for a staggering 681 days—nearly two years—from April 2022 through February 2024.

The exposure demonstrates a fundamental cloud security failure: embedding access credentials in client-side code where they can be viewed by any website visitor. This basic mistake is explicitly warned against in cloud security best practices, yet continues to occur across organizations of all sizes.

### Impact on Individuals
The breach affected approximately 1,600 individuals associated with Australian professional football, including:

**Players**: A-League Women, A-League Men, and A-League Youth athletes
**Team Personnel**: Coaches, trainers, medical staff, and administrative employees
**Family Members**: Relatives of some players whose information was stored
**Ticket Buyers**: Fans who purchased tickets through Football Australia systems

The exposed information included highly sensitive data:
- **Passport details**: Full passport scans showing passport numbers, photos, and personal details
- **Player contracts**: Employment agreements revealing salaries, terms, and confidential clauses
- **Personal contact information**: Addresses, phone numbers, email addresses
- **Identity documents**: Additional verification documents beyond passports

The exposure of passport information is particularly serious:
- Passports are primary identity documents that cannot be easily changed
- Passport scans enable sophisticated identity fraud and document forgery
- International travel patterns and citizenship status may be revealed
- Passport numbers can be used for fraudulent visa applications or border crossings

For professional athletes, the exposure of contract details creates:
- Privacy violations regarding salary and employment terms
- Potential competitive disadvantages if contract clauses are revealed
- Risk of targeted exploitation based on financial information
- Possible contract renegotiation complications

The 681-day exposure window is particularly concerning, as it provided ample time for malicious actors to discover and exploit the publicly accessible data before the vulnerability was identified and remediated.

### Organisational Response
Upon being notified by Cybernews researchers in early February 2024, Football Australia responded promptly to secure the exposed AWS keys and restrict access to the affected data buckets. The organization acknowledged the misconfiguration and took steps to remediate the vulnerability.

Football Australia published a "Data Incident FAQs" document addressing the breach and providing information to affected individuals. The organization:
- Removed the hardcoded AWS keys from the webpage source code
- Rotated all compromised access credentials
- Reviewed access logs to determine if unauthorized parties accessed the data
- Began notifying affected players, personnel, and ticket buyers
- Provided guidance on identity theft protection and passport security

The organization attributed the incident to human error rather than a deliberate attack, explaining that the AWS keys were inadvertently left in the HTML code during development or maintenance activities.

Football Australia worked with cloud security specialists to:
- Conduct a comprehensive audit of all web properties for similar misconfigurations
- Implement code review processes to prevent credential exposure
- Enhance developer training on cloud security best practices
- Deploy automated scanning tools to detect hardcoded secrets in code

The 681-day exposure period raised questions about Football Australia's security monitoring and logging practices. The length of time before discovery suggests:
- Limited or no automated secret scanning in production environments
- Insufficient access log monitoring for unusual patterns
- Lack of regular security audits of public-facing web properties
- Possible absence of cloud security posture management tools

The incident served as a cautionary tale about cloud security fundamentals: credentials must never be embedded in client-side code, and organizations need automated tools to detect and prevent such exposures before they reach production environments.

[extra.impact]
affected_individuals = 1600
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
