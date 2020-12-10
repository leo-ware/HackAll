<h1 align="center">
  <img src="static/logo.png" alt="Hack_All_Logo" width="200px"></a>
  <br>
</h1>


[![License](https://img.shields.io/badge/license-MIT-_red.svg)](https://opensource.org/licenses/MIT)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/projectdiscovery/nuclei/issues)
[![GitHub Release](https://img.shields.io/github/release/markgacoka/HackAll)](https://github.com/markgacoka/HackAll/releases)
[![Chat on Discord](https://img.shields.io/discord/785592691458048080.svg?logo=discord)](https://discord.gg/WA36fdCXqj)
[![Contributors](https://img.shields.io/github/contributors/markgacoka/HackAll)](https://github.com/badges/markgacoka/HackAll/contributors)
[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/badges/graphs/commit-activity)

HackAll is a Bug Bounty automation tool designed to ease recon and vulnerability assessment.

HackAll is designed to test for all classic vulnerabilities in the bug hunting checklist. It startes with reconnaissance, stores the result to a database, then scans for attack vectors in which a potential vulnerability might be in.

## Features
### Proposed Features - Recon
- [ ] Subdomain Enumeration
- [ ] Directory Discovery
- [ ] Port Scanning
- [ ] Javascript Enumeration
- [ ] GitHub Exposed credentials and .git leakage
- [ ] Information Disclosure
- [ ] HTTP Profiling
- [ ] OSINT
- [ ] Custom Wordlist
- [ ] WAF Detection and Technology Lookup

### Proposed Features - Exploitation
- [ ] Account Takeover
- [ ] Authentication Bypass
- [ ] Buffer Overflow
- [ ] Business Logic Bugs
- [ ] Clickjacking
- [ ] * Code Review
- [ ] CORS Related Issues
- [ ] * Credential Stuffing
- [ ] CRLF - Carriage Return Line Feed Injection
- [ ] CSRF - Cross-Site Request Forgery
- [ ] Denial of Service
- [ ] * Encapsulation
- [ ] Error Handling (error messages, stack trace, DB dumps, null pointer exceptions, and network timeout errors.
- [ ] HTTP Header Injection
- [ ] HTTP Request Smuggling
- [ ] HTTP Parameter Pollution
- [ ] Insecure Direct Object Reference
- [ ] JWT Token Impersonation
- [ ] LDAP Injection
- [ ] File Inclusion
- [ ] Malicious File Upload/Wrong Content Type
- [ ] Open Redirect Vulnerability
- [ ] OS Command Injection
- [ ] Password bruteforcing
- [ ] Password Reset Poisoning
- [ ] Privilege Escalation
- [ ] Prototype Pollution
- [ ] Race conditions
- [ ] RCE - Remote Code Execution
- [ ] Server Side Template Injection
- [ ] * Session Invalidation
- [ ] SQL Injection
- [ ] Subdomain takeovers
- [ ] SSRF - Server Side Request Forgery
- [ ] Upload scanners (for SSRF and code injections)
- [ ] * Unicode Injections
- [ ] Web Cache Poisoning
- [ ] WordPress Hacking
- [ ] XML Injection
- [ ] * XPath Injection
- [ ] XSPA - Cross Site Port Attack
- [ ] XSS - Cross site Scripting
- [ ] XXE Injection - XML External Entities Injection

### Made with (For Contributing)
#### Front End
- Next.js (React Framework)
- Material UI

#### Back End
- Flask for API
- Python3 for Security Tools

#### Storage
- SQL Alchemy for storage

## Installation Instructions
### From Github
```bash
git clone https://github.com/markgacoka/HackAll.git
cd HackAll
pip3 install -r requirements.txt
python3 setup.py
HackAll -version
```

### From Binary
```bash
Download latest binary from https://github.com/markgacoka/HackAll/releases

tar -xzvf HackAll-linux-amd64.tar.gz
mv HackAll /usr/local/bin/
HackAll -version
```

## Running HackAll
```
```

## 📋 Notes
Note: Everyone interacting in the HackAll project's codebases, issue trackers and discussion forums is expected to follow the Code of Conduct.

## Thanks to Core Contributors
<table>
  <tr>
  <td align="center"><a href="https://github.com/leo-ware"><img src="https://avatars2.githubusercontent.com/u/54528853" width="100px;" alt=""/><br /><sub><b>Leo Ware</b></sub></a><br /><a href="https://github.com/markgacoka/HackAll/graphs/contributors" title="Frontend and Backend API">
👨‍💻 ⚛️</a></td>

  <td align="center"><a href="https://github.com/markgacoka"><img src="https://avatars2.githubusercontent.com/u/23658445" width="100px;" alt=""/><br /><sub><b>Gacoka Mbui</b></sub></a><br /><a href="https://github.com/markgacoka/HackAll/graphs/contributors" title="Security Tools">
  🛡️</a></td>
  </tr>
</table>

![Made with love in Localhost](https://madewithlove.now.sh/la?heart=true&template=for-the-badge&text=Localhost)


