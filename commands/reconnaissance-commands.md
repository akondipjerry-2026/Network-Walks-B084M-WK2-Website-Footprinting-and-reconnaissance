Reconnaissance Commands

This document contains the commands used during my website footprinting and reconnaissance practical exercise.

1. WHOIS

whois networkwalks.com

Purpose: Retrieves publicly available domain registration information, including registrar and name server details.

2. WhatWeb

whatweb networkwalks.com

Purpose: Identifies technologies and software used by a website.

3. NSLookup

nslookup networkwalks.com

Purpose: Resolves a domain name to its associated IP address and provides DNS information.

4. cURL – HTTP Header Inspection

curl -I https://networkwalks.com

Purpose: Inspects HTTP response headers returned by the website.

5. WAFW00F

wafw00f networkwalks.com

Purpose: Checks whether a Web Application Firewall (WAF) is protecting the website.

6. DNSRecon

dnsrecon -d networkwalks.com

Purpose: Enumerates DNS information associated with the domain.

---

Important Note

These commands are documented for educational purposes. Only perform reconnaissance on systems you own or have permission to assess. Do not publish sensitive target-specific findings without authorisation.
