# shahpasandi.github.io

Personal portfolio of **Mohammad Shahpasandi** (`@THE_VER1TAS`): Cybersecurity Analyst and Splunk Engineer.

**Live site:** https://shahpasandi.github.io

```text
$ whoami --verbose
Mohammad Shahpasandi
focus  : Defensive Security, Blue Teaming, SIEM Engineering
also   : Malware Triage, Incident Response, Threat Hunting
stack  : Splunk, Sysmon (Windows/Linux), Active Directory
```

## What is this

A single-page, terminal-styled site that presents my resume, skills and open-source security work. It is plain HTML, CSS and a few lines of JavaScript. There is no build step, no framework and no tracking.

## Sections

- **about**: who I am and how I work
- **skills**: SIEM, detection engineering, threat hunting, Sysmon, Active Directory
- **projects**: detection and hunting tools, Sysmon configurations, talks and guides
- **resume**: experience and education
- **contact**: GitHub, LinkedIn, email

## Repository layout

```text
.
├── index.html     # the whole site (HTML + CSS + JS)
├── resume.pdf     # linked from the resume section
└── README.md
```

## Run it locally

```bash
git clone https://github.com/shahpasandi/shahpasandi.github.io.git
cd shahpasandi.github.io
python3 -m http.server 8000
# open http://localhost:8000
```

## Deployment

The site is served by GitHub Pages from the `main` branch (root folder). Every push to `main` is published automatically within a few minutes.

## Contact

- LinkedIn: https://www.linkedin.com/in/shahpasandi/
- GitHub: https://github.com/shahpasandi
