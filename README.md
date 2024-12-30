# Blackarch OSINT
A quick cheatsheet for OSINT and social tools available on Blackarch.

Find tools here: https://www.blackarch.org/tools.html

Here are some go-to tools when you want to discover social accounts from a name or an email:

    Sherlock
        Focus: Username-based searching.
        Why it’s useful: Quickly checks hundreds of social media platforms to see if a specific username is taken.

    Maigret
        Focus: Username-based searching (similar to Sherlock).
        Why it’s useful: Supports a large list of websites—sometimes more than Sherlock—and is actively maintained.

    WhatsMyName
        Focus: Username enumeration.
        Why it’s useful: Maintained by the OSINT community; covers a very wide range of sites.

    socialscan
        Focus: Checks both email and username availability on popular platforms.
        Why it’s useful: If you only have an email, it can show you whether that email is registered on various social sites.

    holehe
        Focus: Email-based account discovery.
        Why it’s useful: Given an email address, it attempts logins or password resets on different websites to see if the account exists.

    userrecon / userrecon-py / nexfil
        Focus: Username enumeration across many social networks.
        Why they’re useful: All are quick ways to see if a chosen username is in use across multiple sites.

    socialpwned
        Focus: Email-based search on social networks.
        Why it’s useful: Finds emails that have been published on social media—helpful if you already have the target’s email.

Quick Tips:

Start with an email: Tools like holehe or socialscan can tell you if that email is registered on major sites (Twitter, Instagram, etc.).
Move to username: Once you get a probable username, Sherlock, Maigret, or WhatsMyName can track it across many platforms.
Check social media: If you know they have a strong presence on Twitter or Instagram, you can also use Twint (for Twitter) or Osintgram (for Instagram) to dig deeper.

This workflow often gives you solid leads on someone’s Twitter, Instagram, GitHub, or other platforms. If the person uses the same handle consistently, these tools will help unearth them quickly.



| Name               | Version                 | Category              | Tier                            | Focus     | Description                                                                                                                                                       |
|--------------------|-------------------------|-----------------------|---------------------------------|-----------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| datasploit         | 367.a270d50            | All-in-One Framework  | Highly Versatile and Powerful   | OSINT     | Automated OSINT framework that correlates data from multiple sources, handling emails, domains, and IPs                                                           |
| gasmask            | 172.2527371            | All-in-One Framework  | Highly Versatile and Powerful   | OSINT     | Comprehensive information gathering tool integrating multiple reconnaissance methods                                                                               |
| finalrecon         | 194.f1abf5a            | Web Reconnaissance    | Highly Versatile and Powerful   | OSINT     | All-in-one web reconnaissance tool that automates scanning and data collection from target websites                                                               |
| twint              | 845.e7c8a0c7           | Social Media Analysis | Highly Versatile and Powerful   | Social    | Advanced Twitter scraping tool that works without API limitations                                                                                                 |
| phoneinfoga        | v2.11.0.r0.g5f6156f    | Phone Intelligence    | Specialized yet Highly Effective | OSINT     | Phone number OSINT framework for carrier, location, and associated information                                                                                    |
| h8mail             | 344.ee31c8f            | Email Intelligence    | Specialized yet Highly Effective | Email     | Email OSINT and breach hunting tool with extensive database access                                                                                                |
| skiptracer         | 123.ca40957            | Web Scraping          | Specialized yet Highly Effective | OSINT     | Python-based web scraping framework focused on OSINT without API dependencies                                                                                     |
| maigret            | main.r46.gb90cdb1      | Username Analysis     | Specialized yet Highly Effective | Username | Comprehensive username checker across multiple platforms for digital footprint analysis                                                                            |
| thedorkbox         | 7.43852d3              | Search Techniques     | Specialized yet Highly Effective | OSINT     | Collection of Google Dorks and OSINT queries for discovering hidden data                                                                                          |
| netspionage        | 99.c24f995             | Network Analysis      | Specialized yet Highly Effective | OSINT     | Combined network forensics, OSINT, and attack detection utility                                                                                                   |
| omnibus            | 129.88dbf5d            | Intelligence Framework| Highly Versatile and Powerful   | OSINT     | Framework for intelligence collection, research, and artifact management                                                                                          |
| inquisitor         | 28.12a9ec1             | Corporate Intelligence| Specialized yet Highly Effective | OSINT     | Specialized in gathering OSINT for companies and organizations                                                                                                    |
| whatbreach         | 42.dad6b9f             | Breach Analysis       | Specialized yet Highly Effective | Email     | Tool for checking breached emails and associated database leaks                                                                                                   |
| trape              | 132.6baae24            | Tracking Research     | Specialized Use Case            | OSINT     | People-tracking and session analysis research tool                                                                                                                |
| osintgram          | 1.3.r9.g3c61e53        | Social Media Analysis | Specialized Use Case            | Social    | Interactive Instagram OSINT tool for profile analysis                                                                                                             |
| linkedin2username  | 144.8889f30            | Corporate Intelligence| Specialized Use Case            | Username | Generates username lists from LinkedIn company employees                                                                                                          |
| protosint          | 26.1ee6ee4             | Service Analysis      | Specialized Use Case            | Email     | Investigates ProtonMail accounts and ProtonVPN IP addresses                                                                                                       |
| gitrecon           | 30.6467e78            | Developer Intelligence| Specialized Use Case            | OSINT     | OSINT tool for GitHub/GitLab profiles and repository analysis                                                                                                     |
| darkscrape         | 68.2ca0e37            | Dark Web Analysis     | Specialized Use Case            | OSINT     | Specialized tool for scraping dark websites                                                                                                                       |
| swamp              | 59.3c8be65            | Analytics Analysis    | Specialized Use Case            | OSINT     | Finds associated sites via Google Analytics Tracking IDs                                                                                                          |
| belati             | 72.49577a1            | All-in-One Framework  | Specialized Use Case            | OSINT     | Traditional Swiss Army Knife for OSINT with multiple data collection modules                                                                                      |
| hosthunter         | 158.553f1c7           | Network Analysis      | Specialized Use Case            | OSINT     | Discovers hostnames using OSINT techniques                                                                                                                        |
| token-hunter       | 343.3358a33           | Developer Intelligence| Specialized Use Case            | OSINT     | Searches group snippets, issues, and discussions for tokens                                                                                                       |
| seekr              | 0.4.0                 | All-in-One Framework  | Specialized Use Case            | OSINT     | Multi-purpose OSINT toolkit with web interface                                                                                                                    |
| pasv-agrsv         | 57.6bb54f7            | Automation           | Specialized Use Case            | OSINT     | Passive reconnaissance and OSINT automation script                                                                                                                |
| dirscraper         | 16.e752450            | Web Reconnaissance    | Specialized Use Case            | OSINT     | Discovers and maps directories found in JavaScript files                                                                                                          |
| osinterator        | 3.8447f58            | All-in-One Framework  | Specialized Use Case            | OSINT     | Python-based OSINT collection toolkit                                                                                                                             |
| autosint           | 236.25d292c           | Automation           | Specialized Use Case            | OSINT     | Automates common OSINT tasks                                                                                                                                      |
| citadel            | 95.3b1adbc            | Tool Collection      | Specialized Use Case            | OSINT     | Library of OSINT tools                                                                                                                                            |
| ct-exposer         | 24.71252ac            | Domain Intelligence   | Specialized Use Case            | OSINT     | Discovers subdomains via Certificate Transparency logs                                                                                                            |
| SET                | 8.0.3                 | Penetration Testing   | Highly Versatile and Powerful   | Social    | Industry-standard social engineering toolkit for penetration testing, including phishing, credential harvesting, and payload generation                            |
| Sherlock           | 0.15.0                | Username Analysis     | Highly Versatile and Powerful   | Username | Popular tool for finding usernames across dozens of social networks, widely used by OSINT practitioners                                                          |
| snscrape           | 0.4.3                 | Social Media Scraping| Highly Versatile and Powerful   | Social    | Python-based social network scraper that works without API limitations, especially effective for Twitter/X                                                        |
| social-analyzer    | 0.45                  | Profile Analysis      | Highly Versatile and Powerful   | Social    | Analyzes and finds person profiles across multiple social media platforms with user-friendly interface                                                            |
| fluxion            | v4.10                 | Network Attacks       | Highly Versatile and Powerful   | Social    | Specialized in Wi-Fi-based social engineering attacks including evil twin hotspots and captive portals                                                            |
| websploit          | 4.0.4                 | Multi-purpose Platform| Specialized yet Highly Effective | OSINT     | Platform combining scanning, web exploitation, and social engineering modules                                                                                     |
| socialscan         | 128.5ae42d0           | Platform Analysis     | Specialized yet Highly Effective | Email     | Checks email addresses and usernames for availability across online platforms                                                                                     |
| social-mapper      | 190.92be8da           | Facial Recognition    | Specialized yet Highly Effective | Social    | Performs facial recognition and correlation across social media sites for advanced OSINT                                                                          |
| seeker             | 376.692e531           | Geolocation           | Specialized yet Highly Effective | Social    | Precise geolocation tool using social engineering techniques                                                                                                      |
| socialfish         | 250.a22b58d           | Phishing             | Specialized yet Highly Effective | Social    | Advanced phishing tool with Ngrok integration for quick deployments                                                                                               |
| cloakify           | 117.f45c3b3           | Data Exfiltration    | Specialized Use Case            | OSINT     | Obfuscates and exfiltrates data by disguising it as normal text                                                                                                   |
| phemail            | 28.302b24d            | Email Campaigns       | Specialized Use Case            | Email     | Automates phishing email campaigns for social engineering tests                                                                                                   |
| anontwi            | 1.1b                  | Anonymous Browsing    | Specialized Use Case            | Social    | Provides anonymous navigation for specific social networks (Twitter, Identi.ca)                                                                                   |
| spf                | 85.344ac2f            | Phishing Framework    | Specialized Use Case            | Social    | Social Phish Framework for quick reconnaissance and simple phishing exercises                                                                                     |
| facebrok           | 33.0f6fe8d            | Platform Specific     | Specialized Use Case            | Social    | Facebook-focused social engineering tool                                                                                                                          |
| social-vuln-scanner| 11.91794c6            | Corporate Analysis    | Specialized Use Case            | Social    | Audits publicly available company information for social engineering risks                                                                                        |
| socialpwned        | v2.0.1                | Email Discovery       | Specialized Use Case            | Email     | OSINT tool for discovering emails published on social networks                                                                                                    |
| creepy             | 137.9f60449           | Geolocation           | Specialized Use Case            | OSINT     | Gathers geolocation data from social networking platforms                                                                                                         |
| userrecon-py       | 15.eebd422            | Username Analysis     | Specialized Use Case            | Username | Checks username availability across 187+ social networks                                                                                                          |
| userrecon          | 10.3b56891            | Username Analysis     | Specialized Use Case            | Username | Checks username availability across 75 social networks                                                                                                            |
| pwdlogy            | 14.8b92bcf            | Password Analysis     | Specialized Use Case            | OSINT     | Generates targeted wordlists for social engineering attempts                                                                                                       |
| maigret            | main.r46.gb90cdb1     | Social Analysis       | Highly Versatile and Powerful   | Username | Robust username checker scanning hundreds of sites to find accounts, with excellent coverage and active development                                              |
| sherlock           | 0.15.0                | Social Analysis       | Highly Versatile and Powerful   | Username | Popular multi-site username finder with large user community and active updates                                                                                   |
| whatsmyname        | 2548.5ff612b          | Social Analysis       | Highly Versatile and Powerful   | Username | User and username enumeration across wide range of websites, maintained by OSINT community                                                                        |
| scylla             | 99.621b7b8            | Advanced Recon        | Highly Versatile and Powerful   | OSINT     | Finds advanced information by username, phone number, and other identifiers                                                                                       |
| socialscan         | 128.5ae42d0           | Platform Analysis     | Specialized yet Highly Effective | Email     | Checks both email address and username availability on popular platforms                                                                                          |
| userrecon-py       | 15.eebd422            | Social Analysis       | Specialized yet Highly Effective | Username | Enhanced version of userrecon, covering 187 social networks                                                                                                       |
| nexfil             | 43.4d93c57            | Social Analysis       | Specialized yet Highly Effective | Username | OSINT tool for finding profiles across various platforms                                                                                                          |
| userrecon          | 10.3b56891            | Social Analysis       | Specialized yet Highly Effective | Username | Classic tool for finding usernames across 75 social networks                                                                                                      |
| inguma             | 0.1.1                 | Penetration Testing   | Highly Versatile and Powerful   | OSINT     | Comprehensive framework for penetration testing, including host discovery and brute-forcing                                                                       |
| linkedin2username  | 144.8889f30           | Corporate Intelligence| Specialized yet Highly Effective | Username | OSINT tool for enumerating corporate usernames from LinkedIn data                                                                                                 |
| bridgekeeper       | 57.55c390c            | Corporate Intelligence| Specialized yet Highly Effective | Username | Scrapes employee names from LinkedIn and converts to username formats                                                                                             |
| o365spray          | 160.28d8d1b           | Corporate Attack      | Specialized Use Case            | Username | Username enumeration and password spraying for Microsoft Office 365                                                                                               |
| o365enum           | 19.522a54c            | Corporate Attack      | Specialized Use Case            | Username | Focused on Office 365 user enumeration                                                                                                                            |
| nosqli-user-pass-enum | 18.1b3713a         | Database Attack       | Specialized Use Case            | Username | Enumerates usernames from vulnerable NoSQL-based webapps                                                                                                         |
| smtp-user-enum     | 1.2                   | Protocol Attack       | Specialized Use Case            | Username | Username enumeration via SMTP protocols (EXPN, VRFY, RCPT TO)                                                                                                     |
| ridrelay           | 34.f2fa99c            | Windows Attack        | Specialized Use Case            | Username | Domain username enumeration over SMB without credentials                                                                                                          |
| cachedump          | 1.1                   | Windows Attack        | Specialized Use Case            | Username | Recovers hashed Windows credentials from cache entries                                                                                                            |
| username-anarchy   | 72.e063191            | Username Generation   | Specialized Use Case            | Username | Generates potential usernames for penetration testing                                                                                                             |
| usernamer          | 20.12983f8            | Username Generation   | Specialized Use Case            | Username | Generates usernames/logins from supplied real names                                                                                                              |
| ssh-honeypot       | 113.4bda71c           | Defensive            | Specialized Use Case            | Username | Logs SSH brute-force attempts including usernames and passwords                                                                                                   |
| apache-users       | 2.1                   | Web Server           | Specialized Use Case            | Username | Enumerates Unix system users relying on Apache UserDir module                                                                                                     |
| h8mail             | 344.ee31c8f           | Email Intelligence    | Highly Versatile and Powerful   | Email     | Popular email OSINT and breach hunting tool with extensive database access and multiple data sources                                                              |
| photon             | 328.d88d5f3           | Web Crawler          | Highly Versatile and Powerful   | OSINT     | Fast crawler that extracts URLs, emails, files, website accounts and more with broad coverage                                                                     |
| operative          | 148.163acdf           | Framework            | Highly Versatile and Powerful   | OSINT     | Multi-module framework for gathering information on websites and enterprises including email searches                                                             |
| socialpwned        | v2.0.1.r5.g6af3563    | Social Analysis       | Highly Versatile and Powerful   | Email     | Effectively gathers emails from social networks for targeted OSINT                                                                                                 |
| gomapenum          | v1.1.0.r110.g8b344df  | Corporate Attack      | Highly Versatile and Powerful   | Email     | User enumeration, password bruteforce, and email gathering across multiple platforms (Azure, ADFS, OWA, O365)                                                     |
| holehe             | 434.14da70f           | Account Discovery     | Specialized yet Highly Effective | Email     | Efficiently finds registered accounts from email addresses                                                                                                        |
| buster             | 92.131437e            | Personal OSINT        | Specialized yet Highly Effective | Email     | Finds emails of a person and returns associated information                                                                                                       |
| cr3dov3r           | 47.4e1f784            | Breach Analysis       | Specialized yet Highly Effective | Email     | Searches for public leaks of email addresses and checks credentials against multiple websites                                                                     |
| osint-spy          | 25.03dcf48            | Comprehensive Scan    | Specialized yet Highly Effective | OSINT     | Performs OSINT scans on email, domain, IP address, or organization                                                                                                |
| simplyemail        | 1.4.10.r7.6a42d37     | Email Recon          | Specialized yet Highly Effective | Email     | Fast and easy email reconnaissance framework with extensibility                                                                                                   |
| dnsrecon           | 1.3.1                 | Domain Analysis       | Specialized Use Case            | OSINT     | Domain, subdomain, and email enumeration using Google                                                                                                             |
| goog-mail          | 1                     | Email Harvesting      | Specialized Use Case            | Email     | Enumerates domain emails from Google search results                                                                                                               |
| quickrecon         | 0.3.2                 | Domain Analysis       | Specialized Use Case            | OSINT     | Gathers subdomains, performs zone transfers, collects emails from search engines                                                                                  |
| spoofcheck         | 16.8cce591            | Security Analysis     | Specialized Use Case            | Email     | Checks domain for email protections like SPF, DKIM, DMARC                                                                                                         |
| pwnedornot         | 150.d25d3fa           | Breach Analysis       | Specialized Use Case            | Email     | Finds passwords for compromised email addresses                                                                                                                   |
| whatbreach         | 42.dad6b9f            | Breach Analysis       | Specialized Use Case            | Email     | Locates breached emails and associated databases                                                                                                                  |
| email2phonenumber  | 29.9df9dbe            | Contact Discovery     | Specialized Use Case            | Email     | Attempts to obtain phone numbers from email addresses                                                                                                             |
| pepe               | 13.b81889b            | Paste Analysis        | Specialized Use Case            | Email     | Collects information about email addresses from Pastebin                                                                                                          |
| pastemonitor       | 10.abbceb9            | Monitoring           | Specialized Use Case            | Email     | Monitors Pastebin for daily pastes and alerts on matches                                                                                                          |
| tempomail          | 26.5600ec3            | Testing              | Specialized Use Case            | Email     | Creates temporary email addresses for testing                                                                                                                     |
| bulk-extractor     | 1562.1c67a75          | Forensics            | Specialized Use Case            | Email     | Bulk extraction of emails and other data from disk images                                                                                                         |
| eindeutig          | 20050628_1            | Email Forensics       | Specialized Use Case            | Email     | Specialized tool for examining Outlook Express DBX files                                                                                                          |
| fakemail           | 1                     | Testing              | Specialized Use Case            | Email     | Fake mail server for acceptance testing                                                                                                                           |
| phemail            | 28.302b24d            | Social Engineering    | Specialized Use Case            | Email     | Automates sending phishing emails for testing                                                                                                                     |
| sees               | 67.cd741aa            | Social Engineering    | Specialized Use Case            | Email     | Enhances phishing by mimicking company emails                                                                                                                     |
| simpleemailspoofer | 54.7075f0c            | Social Engineering    | Specialized Use Case            | Email     | Tool for spoofing emails in testing scenarios                                                                                                                     |
| smtptx             | 1                     | Email Testing         | Specialized Use Case            | Email     | Basic tool for sending test emails                                                                                                                                |
| sniffer            | 4.688854e             | Network Analysis      | Specialized Use Case            | OSINT     | Parses packet traces including SMTP emails                                                                                                                        |
| domlink            | 37.1cabd5d            | Domain Analysis       | Specialized Use Case            | OSINT     | Links domains with registered organization names and emails                                                                                                       |
| gitmails           | 71.8aa8411            | Git Analysis          | Specialized Use Case            | Email     | Focuses on collecting email addresses from git commits                                                                                                            |
| hookshot           | 205.df30b85           | Web Analysis          | Specialized Use Case            | Email     | Integrated web scraper and email breach comparison tool                                                                                                           |
| id-entify          | 34.dd064a5            | Domain Intel          | Specialized Use Case            | Email     | Searches for domain-related information including emails                                                                                                          |
| mail-crawl         | 0.1                   | Email Harvesting      | Specialized Use Case            | Email     | Basic tool for harvesting emails from websites                                                                                                                    |
| pirana             | 0.3.1                 | Security Testing      | Specialized Use Case            | Email     | Tests email content filter security                                                                                                                               |
| socialscan         | 128.5ae42d0           | Account Analysis      | Specialized Use Case            | Email     | Checks email and username availability across platforms                                                                                                           |
