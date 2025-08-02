# 🕵 OSINT Cheat Sheet — 2025 Edition

> **A complete guide to Open Source Intelligence (OSINT) — tools, techniques, and workflows for investigators, cybersecurity professionals, and ethical hackers.**  
> Updated regularly with **new tools** and **real-world methods**.

---

## 📌 What is OSINT?
**OSINT (Open Source Intelligence)** is the process of collecting and analyzing publicly available information from online sources.  
It’s used by:
- Ethical Hackers & Penetration Testers
- Cybersecurity Analysts
- Law Enforcement & Investigators
- Journalists & Researchers

⚠ **Ethical Notice:** All activities should be **legal, authorized, and ethical**. Misuse of OSINT tools may result in criminal charges.

---

## 🚀 OSINT Quick Start

**Beginner? Follow this safe flow:**
1. Pick your **target identifier** — username, email, IP, or domain.
2. Search in **publicly available sources** only.
3. Validate results with multiple tools.
4. Document findings with timestamps & sources.

**Pro Tip for Experts:** Automate repetitive searches with scripts or OSINT automation frameworks like [Recon-ng](https://github.com/lanmaster53/recon-ng).

---

## 🔍 Search Engine Operators

| Search Engine | Operator       | Example Use                               |
|--------------|---------------|-------------------------------------------|
| Google       | `site:`       | `site:example.com admin`                   |
| Google       | `filetype:`   | `filetype:pdf site:gov confidential`       |
| Bing         | `ip:`         | `ip:192.168.1.1`                            |
| DuckDuckGo   | `intitle:`    | `intitle:"index of"`                        |
| Yandex       | `mime:`       | `mime:pdf`                                  |

---

## 🖼 Image & Video OSINT

- **[Google Reverse Image Search](https://images.google.com/)**
- **[TinEye](https://tineye.com/)**
- **[Yandex Images](https://yandex.com/images/)**
- **[InVID](https://www.invid-project.eu/tools-and-services/invid-verification-plugin/)** — Video verification & keyframe extraction
- **[ExifTool](https://exiftool.org/)** — Extract hidden metadata from images
- **[FotoForensics](http://fotoforensics.com/)** — Detect image manipulation

---

## 📧 Email & Username Investigation

- **[HaveIBeenPwned](https://haveibeenpwned.com/)** — Data breach check
- **[Hunter.io](https://hunter.io/)** — Email format & source finder
- **[Namechk](https://namechk.com/)** — Social media profile search
- **[Sherlock](https://github.com/sherlock-project/sherlock)** — Username OSINT tool
- **[Holehe](https://github.com/megadose/holehe)** — Check email usage on multiple sites

---

## 🌐 Domain & Website OSINT

- **[Whois Lookup](https://whois.domaintools.com/)**
- **[DNSDumpster](https://dnsdumpster.com/)**
- **[Shodan](https://www.shodan.io/)** — IoT device search
- **[Censys](https://censys.io/)** — Internet-wide scan data
- **[theHarvester](https://github.com/laramies/theHarvester)** — Email, subdomain & host search

---

## 📄 File & Metadata Analysis

- **[FOCA](https://github.com/ElevenPaths/FOCA)**
- **[Metagoofil](https://github.com/laramies/metagoofil)**
- **[ExifTool](https://exiftool.org/)**
- **[strings (Linux command)](https://man7.org/linux/man-pages/man1/strings.1.html)** — Extract readable text from binary files

---

## 🌍 Geolocation OSINT

- **[GeoGuessr](https://www.geoguessr.com/)** — Street view location guessing
- **[Mapillary](https://www.mapillary.com/)**
- **[Google Earth Pro](https://www.google.com/earth/versions/#earth-pro)**
- **[GeoIP Lookup](https://geoiptool.com/)** — IP location

---

## 🛠 Advanced OSINT Tools for Experts

- **[Maltego](https://www.maltego.com/)** — Link analysis & relationship mapping
- **[SpiderFoot](https://www.spiderfoot.net/)** — Automated OSINT collection
- **[Recon-ng](https://github.com/lanmaster53/recon-ng)** — Modular OSINT framework
- **[OSINT Combine Tools](https://www.osintcombine.com/tools)** — Specialized tools for investigators

---

## 📌 OSINT Workflow Example (Email Investigation)

**Scenario:** You have an email `john.doe@example.com`

1. **Check breaches:** HaveIBeenPwned → get leaked passwords/dates  
2. **Verify accounts:** Holehe → check account usage on services  
3. **Search username:** Sherlock → find social profiles  
4. **Scan images:** If social profiles found, run ExifTool on posted images  
5. **Map connections:** Use Maltego to visualize relationships

---

## 📚 Must-Read OSINT Resources

- [OSINT Framework](https://osintframework.com/) — Interactive OSINT tool index
- [Bellingcat OSINT Guide](https://www.bellingcat.com/resources/how-tos/)
- [The Hitchhiker’s Guide to OSINT](https://i-intelligence.eu/uploads/public-documents/OSINT_Handbook_2020.pdf)
- [Michael Bazzell's OSINT Techniques Book](https://inteltechniques.com/book1.html)

---

## 🏷 Tags & Topics
`osint` `open-source-intelligence` `cybersecurity` `infosec` `digital-forensics` `threat-intelligence` `investigation` `security-research` `cheat-sheet` `ethical-hacking` `red-team` `blue-team` `cyber-investigation`

---

## 👨‍💻 Author
**ALPHA** — Cybersecurity Enthusiast & Educator  
**Team:** CYBER GHOST  


---
