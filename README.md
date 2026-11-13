# shahpasandi.github.io

Personal portfolio of **Mohammad Shahpasandi** : Cybersecurity Analyst and Splunk Engineer.

**Live site:** https://shahpasandi.github.io

```text
$ whoami --verbose
Mohammad Shahpasandi
focus  : Splunk engineering: deployment, distributed & clustered architecture, add-on development, automation
also   : SOC operations, Blue Teaming, Detection & Threat Hunting
stack  : Splunk Enterprise / ES, Universal Forwarder, Sysmon, Linux, Python, Bash
```

## What is this

A single-page, terminal-styled site that presents my resume, skills and open-source security work. It is plain HTML, CSS and a few lines of JavaScript. There is no build step, no framework and no tracking.

## Sections

- **about**: who I am and how I work
- **skills**: SIEM, detection engineering, threat hunting, Sysmon, Active Directory
- **projects**: detection and hunting tools, Sysmon configurations, talks and guides
- **contact**: GitHub, LinkedIn, email

## Repository layout

```text
.
├── index.html     # the whole site (HTML + CSS + JS)
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
