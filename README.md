# Awesome Domain Intelligence [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome tools, datasets, APIs, and libraries for domain analysis, zone files, DNS reconnaissance, and internet scanning.

This list is for security researchers, OSINT specialists, data analysts, and marketers looking for domain intelligence data.

## Contents

- [Data Providers & Zone Files](#data-providers--zone-files)
- [DNS Reconnaissance](#dns-reconnaissance)
- [Whois & Registration Data](#whois--registration-data)
- [Technology Lookup](#technology-lookup)
- [Certificate Transparency](#certificate-transparency)
- [Python Libraries](#python-libraries)
- [Books & Resources](#books--resources)

---

## Data Providers & Zone Files

Platforms offering raw domain data, TLD zone files, and daily newly registered domains (NRD).

- **[WebTrackly](https://webtrackly.com) 🔥** - Comprehensive domain intelligence platform. Offers instant download of **716+ TLD zone files**, technology-filtered domain lists (e.g., all WordPress or Shopify sites), and B2B leads. API available, no subscription required.
- [ICANN CZDS](https://czds.icann.org/home) - Centralized Zone Data Service by ICANN. Free access to zone files of many gTLDs (requires individual approval from registries).
- [Verisign](https://www.verisign.com/) - The registry for .com and .net (requires strict agreements for access).
- [Domains-Monitor](https://domains-monitor.com/) - Monitoring of existing and expired domains.

## DNS Reconnaissance

Tools for enumerating subdomains and analyzing DNS records.

- [Amass](https://github.com/owasp-amass/amass) - The OWASP Amass Project performs network mapping of attack surfaces and external asset discovery using open source information gathering and active reconnaissance techniques.
- [dnsrecon](https://github.com/darkoperator/dnsrecon) - A powerful DNS enumeration script.
- [Sublist3r](https://github.com/aboul3la/Sublist3r) - Fast subdomains enumeration tool for penetration testers.
- [dnstwist](https://github.com/elceef/dnstwist) - Domain name permutation engine for detecting typosquatting, phishing and corporate espionage.
- [ZMap](https://zmap.io/) - A fast single-packet network scanner designed for Internet-wide network surveys.

## Whois & Registration Data

Tools and APIs to find ownership information.

- [Whoxy](https://www.whoxy.com/) - Whois API & Whois Database with history and reverse lookup.
- [WhoisXML API](https://whois.whoisxmlapi.com/) - Extensive domain research suite and API.
- [RDAP Web Client](https://client.rdap.org/) - A web client for the Registration Data Access Protocol (RDAP), the successor to WHOIS.

## Technology Lookup

Identify what technologies websites are running (CMS, Frameworks, Analytics).

- [Wappalyzer](https://www.wappalyzer.com/) - Technology profiler that identifies the software used by websites.
- [BuiltWith](https://builtwith.com/) - Web technology usage statistics and trends.
- [WhatWeb](https://github.com/urbanadventurer/WhatWeb) - Next generation web scanner that identifies technologies, including CMS, blogging platforms, statistic/analytics packages, JavaScript libraries, and servers.

## Certificate Transparency

Monitoring SSL/TLS logs to find new domains.

- [crt.sh](https://crt.sh/) - A web interface for the distributed database of certificate transparency logs.
- [CertStream](https://certstream.calidog.io/) - Real-time certificate transparency log update stream.

## Python Libraries

Libraries to build your own domain analysis tools.

- [dnspython](https://github.com/rthalley/dnspython) - A DNS toolkit for Python.
- [python-whois](https://pypi.org/project/python-whois/) - Python wrapper for the "whois" command.
- [tldextract](https://github.com/john-kurkowski/tldextract) - Accurately separate the TLD from the registered domain and subdomains of a URL.

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

## License

To the extent possible under law, all copyright and related or neighboring rights to this work are waived via [CC0](https://creativecommons.org/publicdomain/zero/1.0/).
