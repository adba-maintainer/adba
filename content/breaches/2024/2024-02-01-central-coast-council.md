+++
title = "Central Coast Council"
date = 2024-02-01
draft = false

[taxonomies]
sector = ["Government"]
year = ["2024"]

[extra]
severity = "Minor"
data_types = ["Credit Card"]
attack_vector = "Hacking"
official_status = "Remediation Complete"
source_url = "https://www.centralcoast.nsw.gov.au/council/council-news/update-attempted-payment-system-breach"
archive_link = "https://web.archive.org/web/20240201/centralcoast.nsw.gov.au/payment-breach-update"
+++

### Summary
Central Coast Council in NSW identified a criminal cyber attack on its payment gateway on February 1, 2024, involving card testing fraud where attackers generated random credit card numbers and tested them by making small payments to Council. While hundreds of payment attempts were rejected, fewer than 20 were successful. The attack potentially affected cardholders across Australia, not just Council customers, as similar incidents impacted multiple organizations using the same payment infrastructure.

### What Happened
On February 1, 2024, Central Coast Council detected suspicious activity in its payment gateway system. Criminal actors were conducting a "card testing" attack, a common fraud technique where attackers generate random credit card numbers using algorithms and test whether they are valid by attempting small transactions.

The attackers targeted Council's online payment system to validate stolen or generated card numbers. By making numerous small payment attempts to Council services, the criminals could identify which card numbers were active and functioning. Successfully validated cards could then be used for larger fraudulent purchases elsewhere or sold on dark web marketplaces.

Council's fraud detection systems flagged the unusual pattern of payment attempts. According to a Council spokesperson: "Hundreds of these payment attempts were rejected, but we are aware that fewer than 20 were successful." The successful transactions indicated that some generated card numbers coincidentally matched real, active credit cards.

As a precautionary measure, Council immediately stopped access to the payment gateway via both the Council website and telephone payment systems. This prevented additional testing attempts while the security incident was investigated and remediated.

Importantly, Council clarified that the compromised cards likely belonged to people across Australia who had never conducted business with Central Coast Council. The card testing attack didn't breach Council's customer database; rather, it exploited Council's payment gateway as a tool to validate randomly generated card numbers.

### Impact on Individuals
The incident affected fewer than 20 cardholders whose credit card numbers were successfully tested through unauthorized payment attempts. However, these individuals were not necessarily Central Coast Council customers—they could be anyone in Australia whose card number was coincidentally matched by the attackers' random generation algorithm.

The impact on affected cardholders included:
- **Unauthorized charges**: Small test payments appeared on credit card statements
- **Potential for further fraud**: Validated card numbers could be used for larger fraudulent transactions or sold to other criminals
- **Card replacement**: Affected individuals likely needed to cancel and replace their credit cards
- **Monitoring requirements**: Cardholders needed to closely monitor statements for additional unauthorized activity

The card testing attack type creates an unusual victim profile: people who never interacted with the targeted organization (Central Coast Council) but whose payment cards were coincidentally matched during the testing process.

For the broader community, the incident raised concerns about:
- Payment gateway security across multiple organizations (Council noted "a number of other organisations had been similarly impacted")
- The vulnerability of online payment systems to automated fraud attempts
- The difficulty of protecting against attacks that don't require direct data theft

### Organisational Response
Central Coast Council responded swiftly upon detecting the suspicious payment activity on February 1, 2024:

**Immediate actions:**
- Suspended access to the payment gateway via website and telephone
- Launched investigation with payment service providers
- Alerted relevant authorities and financial institutions
- Published public notifications warning customers of the service disruption

**Communication:**
Council issued an "Update on attempted payment system breach" on its website, explaining the nature of the attack and reassuring the community. The organization emphasized that this was an attack on the payment processing infrastructure rather than a breach of Council's customer data systems.

**Collaboration:**
Council worked with its payment gateway providers to implement solutions preventing similar card testing attacks. The organization noted that multiple other organizations had been similarly impacted, suggesting a coordinated attack campaign targeting the shared payment infrastructure.

**Service restoration:**
Council closed its online payment channel "in the interim" while security measures were enhanced. The temporary disruption inconvenienced customers needing to pay rates, fines, or other Council fees, but protected the payment system from further exploitation.

The incident highlighted vulnerabilities in payment gateway systems that serve multiple organizations. While Council's own systems and customer database were not compromised, the organization bore responsibility for communicating the incident and managing the service disruption.

The attack demonstrated the evolving nature of payment fraud, where criminals leverage automated tools to test thousands of randomly generated card numbers against vulnerable payment systems. Modern payment gateways require robust rate limiting, CAPTCHA protections, and anomaly detection to prevent such abuse.

Council's relatively quick detection (hundreds of attempts rejected before ~20 succeeded) suggested functional fraud monitoring, though questions remained about why any attempts succeeded before the gateway was shut down.

[extra.impact]
affected_individuals = 20
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
