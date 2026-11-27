## Hi, I'm Fernando

**Offensive & defensive security.** I build security tools in Python, C and C#
to understand how attacks work and how they get detected.

Based in Portugal · [LinkedIn](https://www.linkedin.com/in/fernando-beca/)

### Featured projects

**[LogSentinel](https://github.com/FMBeca/logsentinel)**: detects attacks in Linux and web server logs
and maps every alert to MITRE ATT&CK.

- **SSH:** brute force, password spraying and successful logins after an attack
- **Web (Apache/Nginx):** SQL injection, XSS, path traversal, Log4Shell and directory brute force,
  including scanners that hide behind a browser User-Agent
- **Custom rules** in Sigma format (web and sshd), a self-contained **HTML report**
  and optional IP reputation from AbuseIPDB
- Python with no required dependencies, tested with pytest in GitHub Actions CI
  and against real Ubuntu / OpenSSH 10 logs from my lab

**[MailSentinel](https://github.com/FMBeca/mailsentinel)**: triages a suspicious email (`.eml`) and
returns a scored verdict, with every reason mapped to MITRE ATT&CK.

- **Sender:** SPF, DKIM and DMARC results, misleading display names, replies diverted elsewhere
  and look-alike domains (typos, homoglyphs, punycode)
- **Links and attachments:** link text that hides the real destination, password forms,
  executables, macros and disguised file names, with SHA-256 hashes
- Defanged indicators ready to share, JSON output and exit codes for scripts;
  Python with no required dependencies, works offline

### Focus areas

- **Offensive:** penetration testing, enumeration and exploitation in lab environments
- **Defensive:** log and phishing email analysis, detection engineering, MITRE ATT&CK
- **Tooling:** writing my own security tools instead of only running existing ones

### Tech

Python · C · C# · Linux · Git · GitHub Actions

### Roadmap

- [x] LogSentinel: SSH attack detection
- [x] LogSentinel: web attack detection
- [x] LogSentinel v1.0: Sigma rules and an HTML report
- [x] LogSentinel v1.1: Sigma rules for SSH logs and IP reputation
- [x] MailSentinel v0.1: phishing email triage
- [ ] Port and service scanner in Python
- [ ] Windows / Active Directory enumeration tool in C#
- [ ] CTF and lab write-ups

> All offensive work is done in my own labs or on authorized platforms.
