---
layout: article
title: "Russian Hackers Target 270 Belgian Firms via Fortinet Breach"
date: 2026-06-23 10:50:00 +0000
category: politics
image: /Patria4/assets/img/articles/2026-06-23-russian-hackers-target-270-belgian-firms-via-forti-header.jpg
excerpt: "A critical supply chain vulnerability in a security vendor's partner portal grants Russian actors simultaneous access to hundreds of Belgian networks."
sources:
  - label: "Brussels Times — 270 Belgian organisations targeted"
    url: "https://www.brusselstimes.com/2204554/at-least-270-belgian-organisations-targeted-by-ongoing-russian-cyberattack"
  - label: "TechCrunch — Fortinet firewalls hacked"
    url: "https://techcrunch.com/2026/06/17/cybercriminals-allegedly-hacked-tens-of-thousands-of-fortinet-firewalls-used-by-major-companies-all-over-the-world/"
  - label: "SOCRadar — FortiBleed 2026 impact"
    url: "https://socradar.io/blog/fortibleed-fortinet-firewalls-compromised/"
  - label: "BleepingComputer — VPN credentials leak"
    url: "https://www.bleepingcomputer.com/news/security/fortibleed-leak-exposes-fortinet-vpn-credentials-for-73-000-devices/"
  - label: "VRT NWS — Belgian companies hacked via Fortinet"
    url: "https://www.vrt.be/vrtnws/nl/2026/06/22/belgische-bedrijven-gehackt/"
  - label: "CCB Belgium — Cyber Emergency Response Team"
    url: "https://ccb.belgium.be/cert"
---

Cybersecurity firm Secutec warned on June 23, 2026, that at least 270 Belgian organisations, including schools, law firms, and local authorities, have been compromised by a Russian-speaking cyberattack dubbed "FortiBleed." The breach exploits stolen credentials from Fortinet firewalls, revealing a critical supply chain vulnerability where a single point of failure in a trusted partner portal has granted foreign adversaries simultaneous access to hundreds of downstream networks.

The "FortiBleed" campaign targets Fortinet firewalls and VPN gateways, relying on a combination of brute-force attacks and the use of stolen credentials. The root cause was a February 2026 breach of Fortinet's partner portal, which allowed Russian-speaking hackers to harvest login data from tens of thousands of IT service providers. This breach acted as a force multiplier, granting the attackers a map and the keys to downstream client networks. Globally, the impact is massive; over 110 million login credentials have been stolen, with estimates of compromised devices ranging from 73,000 according to BleepingComputer to over 86,000 reported by SOCRadar and CISA. High-profile global victims include Accenture, Comcast, Foxconn, Lenovo, Oracle, Samsung, Siemens, and PwC. In Belgium, at least 270 organisations—including local authorities, law firms, and schools—have been impacted.

The scale of the vulnerability remains acute. Geert Baudewijns, CEO of the cybersecurity firm Secutec, warned that the attack highlights a systemic failure in basic security hygiene. "A single weak link can grant simultaneous access to hundreds of organisations," Baudewijns stated, noting that the persistence of 'admin/admin' logins in 2026 is "simply not possible." This "admin/admin" paradox reveals that despite the high-tech nature of the Russian campaign, many Belgian firms were compromised via default credentials, rendering the sophisticated hardware of their firewalls irrelevant. Secutec identified 1,300 cases of firewalls using these default credentials globally, with a significant portion of the 270 Belgian entities still exposed. Currently, 110 firewalls from affected Belgian organisations remain accessible, and in 45 systems, hackers have already created new accounts to maintain persistent access for sale on the dark web.

The response from the vendor and authorities reflects a tension between product integrity and operational reality. Tiffany Curci, a spokesperson for Fortinet, stated that the company is aware of the "third-party credential-harvesting campaign" but emphasized that the issue is a "resharing of data from previous incidents" and "bruteforcing," rather than a new software vulnerability in the product itself. Meanwhile, the Centre for Cybersecurity Belgium (CCB) has been officially informed of the breaches. Under the NIS2 Law of April 2024, the CCB is coordinating the response across the 270 affected entities, as the law mandates stricter cybersecurity requirements for "essential" and "important" entities, including the schools and local governments hit in this wave.

This event demonstrates the critical risk of the IT supply chain trap, where the trust placed in a single security vendor's partner ecosystem becomes the primary vector of failure. Security researchers, including Bob Diachenko and teams at SOCRadar, have characterized the campaign as a "systematic dismantling of the perimeter model." By compromising the partner portal, Russian actors bypassed the perimeter security of hundreds of Belgian entities simultaneously without needing to exploit a zero-day vulnerability. The objective of the operation is not merely immediate data theft but the creation of "initial access" as a commodity. These backdoors are then sold on the dark web to other ransomware operators, transforming a single vendor leak into a permanent, scalable entry point for foreign adversaries into European critical infrastructure.

The incident highlights a stark contradiction in the current threat landscape: while SOCRadar and CISA identify this as an ongoing campaign with new victims still being added, Fortinet frames the event as a "credential-harvesting campaign" based on old data. This discrepancy underscores the difficulty in containing a breach once credentials enter the dark web ecosystem, where they are traded and reused by various Russian-speaking threat actors.

The Centre for Cybersecurity Belgium (CCB) continues to coordinate the response across the 270 affected entities as the full extent of the "FortiBleed" impact is assessed. With 110 firewalls still accessible and 45 systems containing persistent backdoor accounts, the immediate priority remains the rotation of credentials and the auditing of partner-level access. The incident leaves an open question for European critical infrastructure: how to mitigate the systemic risk when a single global security vendor's partner ecosystem becomes the primary entry point for foreign adversaries.
