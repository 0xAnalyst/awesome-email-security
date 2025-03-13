# Awesome Email Security [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
A curated list of awesome resources related to enhancing your enterprise Email Security. Learn about email security protocols and best practices. Contributions are welcome!

![email](https://github.com/0xAnalyst/Awesome-Email-Security/assets/893075/726101a0-ab4d-4534-9aab-9daf5d2a6716)


## Contents

* [Email Authentication](#email-authentication) 
* [Email Filtering](#email-filtering) 
* [Email Encryption](#email-encryption) 
* [Phishing Protection](#phishing-protection) 
* [Tools](#tools)
* [Reading](#reading)
  
## Email Authentication

### SPF (Sender Policy Framework)
* [SPF Introduction](https://powerdmarc.com/what-is-spf/) - SPF Explanation by PowerDMARC.
* [SPF Introduction Dmarcian](https://dmarcian.com/what-is-spf/)   - SPF Explanation by Dmarcian.
* [SPF Record Setup](https://powerdmarc.com/how-to-setup-spf/) - SPF Record Setup by PowerDMARC.
* [SPF Macros](https://duo.com/labs/tech-notes/detecting-phishing-with-spf-macros) - SPF Macro Explanation.

### DKIM (DomainKeys Identified Mail)
* [DKIM Technical Details](https://easydmarc.com/blog/what-is-a-dkim-signature/) - Technical Deep Dive on DKIM.
* [DKIM Record Configuration](https://help.ovhcloud.com/csm/en-dns-zone-dkim?id=kb_article_view&sysparm_article=KB0058258) - Configuring a DKIM record.
#### DMARC (Domain-based Message Authentication, Reporting, and Conformance)
* [DMARC Introduction](https://www.techfry.com/webmaster-tips/domain-based-message-authentication-reporting-conformance-dmarc) -  An introductory explanation of DMARC and how it works.
* [DMARC Explanation](https://www.mailmodo.com/guides/dmarc/) - Good DMARC alignment explanation.

#### BIMI (Brand Indicators for Message Identification)
* [BIMI Complete Guide](https://powerdmarc.com/your-complete-guide-to-bimi/) - BIMI Introduction and Compelete guide.
* [BIMI Implementation Guide](https://bimigroup.org/implementation-guide/) -  BIMI Group Implementation guide.

#### MTA-STS (Mail Transfer Agent Strict Transport Security)
* [MTA-STS Introduction and Implementation](https://powerdmarc.com/what-is-mta-sts-and-why-do-you-need-it/) -  A guide on MTA-STS by PowerDMARC.

## Email Filtering

### Anti-Spam Solutions
* [Email Filtering concepts](https://abnormalsecurity.com/glossary/email-filters) - Introduction to Email Filtering concepts and different types of spam filtering.
* [Exchange Online Email Filtering](https://learn.microsoft.com/en-us/defender-office-365/eop-about) - Exchange Online Email Filtering Details.

### File Extensions Filtering

* [List of File Extensions to Block](https://github.com/0xAnalyst/awesome-email-security/blob/main/FileExtensionstoblock.md) - A list of file extensions to block depending on your policy.

## Email Encryption
### Transport Layer Security (TLS) for Email Transport
* [STARTTLS](https://emaillabs.io/en/what-is-starttls/) - An Explainer for STARTTLS and Opportunistic TLS vs Forced TLS.
* [Email Transport Encryption Protocols](https://certified-senders.org/wp-content/uploads/2020/02/Email-Transport-Encryption-STARTTLS-vs.-DANE-vs.-MTA-STS_updated.pdf) - Explains the difference between STARTTLS, DANE, MTA-STS.
### S/MIME Secure – Multipurpose Internet Mail Extensions
* [S/MIME Introduction](https://docs.servicenow.com/bundle/washingtondc-platform-administration/page/administer/notification/concept/smime-inbound-outbound-mails.html) - S/MIME Introduction. 
### Open PGP Open Pretty Good Privacy
* [Introduction to Open PGP](https://www.first.org/pgp/An_Introduction_to_PGP-GnuPG_v1.0.pdf) - Open PGP Intro.
### GPG GNU Privacy Guard

## Phishing Protection
### Email Content Analysis for Phishing Detection
* [Sublime Rules](https://github.com/sublime-security/sublime-rules) - Sublime Security Open Source Detection Rules.
* [Phishing Detection Keywords](https://github.com/0xAnalyst/Awesome-Email-Security/blob/main/PhishingKeywords) - Phishing Detection Keywords to check for.

## Tools
### Email Header Analysis
* [Microsoft MHA](https://mha.azurewebsites.net/) - Microsoft Email Header Analysis.
* [MxToolBox MHA](https://mxtoolbox.com/EmailHeaders.aspx) - MxToolBox Email Header Analyzer.
* [CyberDefenders MHA](https://github.com/cyberdefenders/email-header-analyzer) - Excellent Email Header Analyzer that can be deployed locally.

### DMARC Reports Analysis
* [MxToolBox DMARC Report Analyzer](https://mxtoolbox.com/DmarcReportAnalyzer.aspx) - MxToolBox DMARC Report Analyzer.
* [Open Source DMARC Report Analyzer](https://github.com/userjack6880/Open-DMARC-Analyzer) - Open Source DMARC Report Analyzer. 

### Commercial Email Security Tools
### Open Source Email Security Tools
* [DMARC Record Analyzer](https://github.com/cisagov/trustymail) - CISA SPF/DMARC Record Analyzer.
* [DMARC Report Parser](https://github.com/domainaware/parsedmarc) - DMARC Report Parser.
* [DMARC Report Parser](https://github.com/emalderson/ThePhish) - ThePhish is an automated phishing email analysis tool based on TheHive, Cortex and MISP.

## Reading
### Books
* [Email Security: Attack and Defence](https://leanpub.com/emailsecattackanddefence) - A book on Email Security.
  

