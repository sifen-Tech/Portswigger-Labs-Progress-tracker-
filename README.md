# PortSwigger Web Security Academy - Solved Labs

![Total Labs](https://img.shields.io/badge/Total%20Labs%20Solved-0-blue) ![Last Updated](https://img.shields.io/badge/Last%20Updated-2026--00--00-yellow) ![Level](https://img.shields.io/badge/Level-NEWBIE-green) ![Vulnerability labs](https://img.shields.io/badge/Completed-0%25-purple)

This file tracks my progress through [PortSwigger Web Security Academy](https://portswigger.net/web-security) labs. I focus on web app pentesting, documenting key labs as full writeups (linked below) and logging all solves here for reference. Full writeups are reserved for first-time techniques, complex exploits, or custom tools.

## Level progress
- **Apprentice**: 26 of 61
- **Practitioner**: 37 of 174
- **Expert**: 0 of 39

## Categories Covered

- **Authentication vulnerabilities**: 12/14 lab
- **SQL injection**: 14/18 lab
- **Access control**: 13/13 lab
- **Path traversal**: 6/6 lab
- **OS Command injection**:5/5 lab
- **Information disclosure**:1/5
- **File upload vulnerabilities**:6/7
- **Business logic vulnerebilities**:4/12
- **Race conditions**:2/6

## Notes
- **Full Writeups**: Only for significant labs (e.g., chained exploits or scripted solutions). See `platforms/portswigger/` for details.
- **Tools Used**: Burp Suite

## How to Read
- **Columns**: 
  - `No`: Sequential lab number.
  - `Date`: When I solved it (YYYY-MM-DD).
  - `Topic`: Vulnerability category (e.g., API Testing, XSS).
  - `Lab Title`: Exact name from PortSwigger.
  - `Difficulty`: Apprentice, Practitioner, or Expert.
  - `Writeup Link`: Links to full writeup (if exists) or "N/A" for quick solves.

---

## Solved Labs

| No | Date       | Topic            | Lab Title                                   | Difficulty  | Writeup Link |
|----|------------|----------------|---------------------------------------------|-------------|--------------|
| 1  | 2026-06-17 |  SQL injection   |SQL injection vulnerability in WHERE clause allowing retrieval of hidden data                                                                                            | Apprentice  | N/A |
| 2  | 2026-06-17 | SQL injection    |SQL injection vulnerability allowing login bypass  | Apprentice | N/A |
| 3  | 2026-06-17 |  SQL injection   |SQL injection attack, querying the database type and version on Oracle  | practitioner | N/A |
| 4  | 2026-06-18 | SQL injection    |SQL injection attack, querying the database type and version on MySQL and Microsoft  |practitioner  | N/A |
| 5  | 2026-06-18 | SQL injection    |SQL injection attack, listing the database contents on non-Oracle databases  |practitioner  | N/A |
|6 | 2026-06-18 |SQL injection  | SQL injection attack, listing the database contents on Oracle|practitioner|N/A|
|7|2026-06-19|SQL injection |SQL injection UNION attack, determining the number of columns returned by the query|practitioner|N/A|
|8|2026-06-19|SQL injection |SQL injection UNION attack, finding a column containing text|practitioner|N/A|
|9|2026-06-19|SQL injection|SQL injection UNION attack, retrieving data from other tables|practitioner|N/A|
|10|2026-06-20|SQL injection|SQL injection UNION attack, retrieving multiple values in a single column|practitioner|N/A|
|11|2026-06-20|SQL injection|Visible error-based SQL injection|practitioner|N/A|
|12|2026-06-20|SQL injection|Blind SQL injection with time delays|practitioner|N/A|
|13|2026-06-23|Authentication vulnerebilities|Username enumeration via different responses|Apprentice|[this](https://github.com/sifen-Tech/Portswigger-Labs-Progress-tracker-/blob/main/portswigger_write-up/write-up)|
|14|2026-06-23|Authentication vulnerebilities|2FA simple bypass|Apprentice|N/A|
|15|2026-06-25|Authentication vulnerebilities|Password reset broken logic|Apprentice|N/A|
|16|2026-06-25|Authentication Vulnerebilities|Password reset poisoning via middleware|Practitioner|N/A|
|17|2026-06-26|SQL injection|SQL injection with filter bypass via XML encoding|practitioner|N/A|
|18|2026-06-26|Authentication vulnerebilities|Offline password cracking|practitioner|N/A|
|19|2026-06-26|Authentication vulnerebilities|Password brute-force via password change|practitioner|N/A|
|20|2026-06-28|SQL injection|Blind SQL injection with conditional errors|practitioner|N/A|
|21|2026-06-28|Authentication vulnerebilities|Broken brute-force protection, IP block|practitioner|N/A|
|22|2026-06-28|Authentication vulnerebilities|Brute-forcing a stay-logged-in cookie|practitioner|N/A|
|23|2026-06-30|Path traversal|File path traversal, simple case|Apprentice|N/A|
|24|2026-06-30|Path traversal|File path traversal, traversal sequences blocked with absolute path bypass|practitioner|N/A|
|25|2026-06-30|Path traversal| File path traversal, traversal sequences stripped non-recursively|practitioner|N/A|
|26|2026-06-30|Path traversal|  File path traversal, traversal sequences stripped with superfluous URL-decode|practitioner|N/A|
|27|2026-06-30|Path traversal| File path traversal, validation of start of path|practitioner|N/A|
|28|2026-06-30|Path traversal| File path traversal, validation of file extension with null byte bypass|practitioner|N/A|
|29|2026-07-02|OS Command injection| OS command injection, simple case|Apprentice|N/A|
|30|2026-07-02|OS Command injection|  Blind OS command injection with time delays|Practitioner|N/A|
|31|2026-07-02|OS Command injection|  Blind OS command injection with output redirection|Practitioner|N/A|
|32|2026-07-02|OS Command injection|  Blind OS command injection with out-of-band interaction|Practitioner|N/A|
|33|2026-07-05|Authentication vulnerebility|2FA broken logic|practitioner|N/A|
|34|2026-07-05|OS Command injection|Blind OS command injection with out-of-band data exfiltration|practitioner|N/A|
|35|2026-07-05|Authentication vulnerebility| Username enumeration via account lock|practitioner|N/A|
|36|2026-07-05|Authentication vulnerebility|  Username enumeration via subtly different responses|practitioner|N/A|
|37|2026-07-05|Authentication vulnerebility| Username enumeration via response timing|practitioner|N/A|
|38|2026-07-07|Access control|Unprotected admin functionality|Apperentice|N/A|
|39|2026-07-07|Access control|Unprotected admin functionality with unpredictable URL|Apperentice|N/A|
|40|2026-07-08|Access control|User role controlled by request parameter|Apprentice|N/A|
|41|2026-07-08|Access control|User role can be modified in user profile|Apprentice|N/A|
|42|2026-07-09|Access control| Insecure direct object references|Apprentice|N/A|
|43|2026-07-09|Information disclosure |Information disclosure in error messages|Apprentice|N/A|
|44|2026-07-11|Access control| User ID controlled by request parameter|Apprentice|N/A|
|45|2026-07-11|Access control|  User ID controlled by request parameter with data leakage in redirect|Apprentice|N/A|
|46|2026-07-11|Access control| User ID controlled by request parameter, with unpredictable user IDs|Apprentice|N/A|
|47|2026-07-11|Access control| User ID controlled by request parameter with password disclosure|Apprentice|N/A|
|48|2026-07-13|Access control| URL-based access control can be circumvented|practitioner|N/A|
|49|2026-07-13|Access control| Method-based access control can be circumvented|practitioner|N/A|
|50|2026-07-14|File upload vulnerabilities| Remote code execution via web shell upload|Apprentice|N/A|
|51|2026-07-14|File upload vulnerabilities| Web shell upload via Content-Type restriction bypass|Apprentice|N/A|
|52|2026-07-15|File upload vulnerabilities| Web shell upload via path traversal|practitioner|N/A|
|53|2026-07-15|File upload vulnerabilities|Web shell upload via extension blacklist bypass|practitioner|N/A|
|54|2026-07-16|File upload vulnerabilities|Web shell upload via obfuscated file extension|practitioner|N/A|
|55|2026-07-16|File upload vulnerabilities| Remote code execution via polyglot web shell upload|practitioner|N/A|
|56|2026-07-17|Access control|Multi-step process with no access control on one step|practitioner|N/A|
|57|2026-07-17|Access control| Referer-based access control|practitioner|N/A|
|58|2026-07-18|Business logic vulneribilities| Excessive trust in client-side controls|Apprentice|N/A|
|59|2026-07-18|Business logic vulneribilities| High-level logic vulnerability|Apprentice|N/A|
|60|2026-07-19|Business logic vulneribilities| Inconsistent security controls|Apprentice|N/A|
|61|2026-07-19|Business logic vulneribilities| Flawed enforcement of business rules|Apprentice|N/A|
|62|2026-07-22|Race conditions|Limit overrun race conditions|Apprentice|N/A|
|63|2026-07-22|Race conditions|Bypassing rate limits via race conditions|practitioner|N/A|












