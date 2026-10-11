# B.Cyber & Bug Bounty Master Roadmap

A production-ready, interactive vertical flowchart roadmap website inspired by **[roadmap.sh](https://roadmap.sh)** and GitHub Dark theme, built for students preparing for the **IIT Kanpur B.Cyber Hackathon**, technical challenge rounds, and bug bounty hunting.

![Theme](https://img.shields.io/badge/Theme-GitHub%20Dark-161b22?style=flat-square)
![Stack](https://img.shields.io/badge/Tech-Vanilla%20HTML%2FCSS%2FJS-58a6ff?style=flat-square)
![Performance](https://img.shields.io/badge/Zero%20Dependencies-Standalone-3fb950?style=flat-square)

---

## ⚡ Features

- **Vertical Timeline Architecture**: Central glowing trunk line connecting 13 structured milestone nodes across 4 sequential phases.
- **Weekly Cadence Dashboard**: Visual 5-box weekly study split across Web/API, Reversing, Networking/OSINT, PoW Tools, and Write-ups.
- **Interactive Checklists & Persistence**: Checkboxes persist state directly to browser `localStorage` across reloads with smooth progress animations.
- **Instant Search & Category Filters**: Real-time filtering by tools (Burp, Ghidra, Wireshark, GDB), vulnerabilities (IDOR, JWT, SQLi, XSS), or categories.
- **Collapsible Definition Drawers**: Beginner-friendly `<details>` accordions defining every technical term across every card.
- **Single-File Zero Dependency Architecture**: Completely self-contained in `index.html` with zero build steps or heavy frameworks.

---

## 🗺️ Roadmap Curriculum Overview

### Phase 1: Core Web, Terminal & Automation (Months 1–3)
- **Step 1: Linux Command-Line Fluency** — OverTheWire Bandit (L1–25), permissions, piping, redirection.
- **Step 2: Python Network Automation & Port Scanner** — Low-level sockets, multi-threading, connect vs SYN scans.
- **Step 3: Web Vulnerability Foundations & Burp Suite** — PortSwigger Academy, SQLi, XSS, Path Traversal, Repeater.

### Phase 2: APIs, Network Traffic, OSINT & Access Control (Months 4–6)
- **Step 4: API Security, Modern Authentication & IDOR** — OWASP API Top 10, BOLA/IDOR, JWT manipulation, GraphQL.
- **Step 5: Network Traffic Analysis & Protocol Inspection** — TryHackMe, Wireshark packet capture analysis, ARP spoofing.
- **Step 6: OSINT & Threat Footprinting** — Google Dorking, Shodan, theHarvester, EXIF metadata, CTF recon.

### Phase 3: Reverse Engineering, Assembly & Cryptography (Months 7–9)
- **Step 7: Reverse Engineering 101 & Disassembly** — Malware Unicorn RE 101, x86/x64 registers, stack frames, Ghidra.
- **Step 8: Hands-On Binary Cracking & Flag Extraction** — Crackmes.one, picoCTF reversing, GDB runtime breakpoints.
- **Step 9: Practical Cryptography & Scripting Attacks** — XOR ciphers, modular math, RSA small-e, CyberChef recipes.
- **Step 10: Privilege Escalation Foundations** — TryHackMe Linux & Windows PrivEsc, SUID, GTFOBins, token manipulation.

### Phase 4: Live CTFs, VDP Bug Bounties & Shortlist Defense (Months 10–12)
- **Step 11: Competitive CTFs & Speed Drills** — CTFtime.org, solo 6h timed simulations, exploit cheat sheets.
- **Step 12: VDP Hunting & Real-World Bug Bounty Testing** — HackerOne / Bugcrowd VDPs, IDOR, triage reporting.
- **Step 13: Portfolio Packaging & B.Cyber Shortlist Freeze** — Tool documentation, 5 technical write-ups, proof-of-work.

---

## 🚀 Running Locally

No installation or build tools required. Simply open `index.html` in any modern web browser:

```bash
# Clone the repository
git clone https://github.com/an5hT/roadmap.git

# Navigate into directory
cd roadmap

# Open index.html directly in browser
open index.html   # On macOS
start index.html  # On Windows
xdg-open index.html # On Linux
```

Or run with a simple local server:
```bash
python -m http.server 8080
```
Then visit `http://localhost:8080` in your browser.
