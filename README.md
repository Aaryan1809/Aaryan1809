<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:22D3EE,100:8B5CF6&height=6" width="100%" alt="Cyan to violet divider" />
</p>

<h1 align="center">Aaryan Soni</h1>

<p align="center">
  <b>Cybersecurity &nbsp;·&nbsp; IoT &amp; Embedded Systems &nbsp;·&nbsp; Applied AI</b>
</p>

<p align="center">
  <i>Learning by testing systems, building prototypes, and documenting what actually works.</i>
</p>

<p align="center">
  <a href="https://github.com/Aaryan1809"><img src="https://img.shields.io/badge/GitHub-Aaryan1809-0D1117?style=flat-square&logo=github&logoColor=22D3EE" alt="GitHub profile" /></a>
  <a href="mailto:aaryanthepiccoder@gmail.com"><img src="https://img.shields.io/badge/Email-aaryanthepiccoder%40gmail.com-0D1117?style=flat-square&logo=gmail&logoColor=8B5CF6" alt="Email Aaryan" /></a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:22D3EE,100:8B5CF6&height=2" width="100%" alt="" />
</p>

## About Me
Curious Learner

- **Cybersecurity & networking:** Linux, scanning, enumeration, and web-security labs, done only on systems I own or am authorized to test.
- **IoT & embedded systems:** an ESP32 board, the Arduino IDE, and a lot of troubleshooting (USB ports, firmware uploads, Wi-Fi behavior).
- **Applied AI & automation:** connecting LLMs, APIs, and workflow tools to solve small practical problems instead of just adding a chatbot.

Most of what's here is learning in progress. I label each project honestly by how far along it is.

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:22D3EE,100:8B5CF6&height=2" width="100%" alt="" />
</p>

## Current Builds & Research

These are projects at different stages. None of them should be read as finished or production-ready. Status legend:
![Prototype](https://img.shields.io/badge/-Prototype-8B5CF6?style=flat-square&labelColor=0D1117)
![Exploring](https://img.shields.io/badge/-Exploring-22D3EE?style=flat-square&labelColor=0D1117)
![Planned](https://img.shields.io/badge/-Planned-6B7280?style=flat-square&labelColor=0D1117)

### ESP32 Smart Sensing Lab &nbsp; ![Prototype](https://img.shields.io/badge/-Prototype%20%26%20architecture%20exploration-8B5CF6?style=flat-square&labelColor=0D1117)

Hands-on experiments with an ESP32 development board, plus the architecture for a sensor-driven monitoring system.

- Done so far: Arduino IDE firmware uploads, serial monitoring, Wi-Fi access-point experiments, and looking at information about devices connected to the ESP32's access point.
- Attempted: Wi-Fi Channel State Information (CSI) collection, with Python scripts writing the data to CSV. It did **not** capture the expected data yet, and I'm still troubleshooting it.
- Concept: measure things like temperature and moisture, send the readings to a dashboard, and eventually add an analysis layer. A team of four, which I led, took this concept to the **Round-II budget-negotiation stage of CHARUSAT SSIP Pitching 2026-27**.
- Not built yet: the cloud pipeline, the dashboard, and AI analysis are all still design work.

`ESP32` `Arduino IDE` `Wi-Fi` `Sensors` `Data collection` `IoT architecture`

### LLM-Assisted Workflow Automation &nbsp; ![Exploring](https://img.shields.io/badge/-Learning%20%26%20prototyping-22D3EE?style=flat-square&labelColor=0D1117)

Multi-step automation for useful, repetitive tasks, such as handling messages, lead details, and follow-ups. The aim is to automate real work, not to build a bot that just answers questions.

- Tools I'm working with: n8n, Telegram bots, Google Sheets, Gmail and Google APIs, webhooks, and LLM integrations.
- One use case I've explored is receptionist and admission-assistant style workflows for small local businesses.
- This is API orchestration and prompt-driven workflow design. It is not ML model training.

`n8n` `Telegram` `Google Sheets` `Gmail` `Webhooks` `APIs` `LLM integrations`

### Android / Termux Home File Server &nbsp; ![Planned](https://img.shields.io/badge/-Planned%20%2F%20early%20experiment-6B7280?style=flat-square&labelColor=0D1117)

An experiment in self-hosting: turning a spare Android 9 phone (Wi-Fi only, no SIM) running Termux into a private, local-network file server for my family's business images, so they stop filling up a main phone.

- Learning goals: Linux command-line tools, local networking, file transfer, access control and authentication, storage management, and backups.
- Not deployed, and not yet validated as secure. Security design comes before anything gets used for real files.

`Termux` `Linux CLI` `Local networking` `File transfer` `Access control` `Backups`

### Cybersecurity Lab Journal &nbsp; ![Exploring](https://img.shields.io/badge/-Ongoing%20learning-22D3EE?style=flat-square&labelColor=0D1117)

A growing collection of notes from controlled lab environments: reproducible steps, safe proof-of-concept scripts, findings, and lessons learned.

- Topics: Linux and networking exercises, reconnaissance, scanning, enumeration, vulnerability analysis, and basic Python networking scripts (including TCP client/server and network discovery).
- Environments: TryHackMe, PortSwigger Web Security Academy, and intentionally vulnerable practice machines such as Metasploitable.
- Tools studied or used: Kali Linux, Nmap, Burp Suite, Metasploit Framework.
- Ground rules: authorized, legal testing only, on systems I own or have permission to assess. I'll link individual write-ups here as they're published.

`Kali Linux` `Nmap` `Burp Suite` `Metasploit` `PortSwigger Academy` `TryHackMe`

#### Roadmap idea

**IoT Anomaly Detection System** &nbsp; ![Planned](https://img.shields.io/badge/-Planned-6B7280?style=flat-square&labelColor=0D1117)
Collect real sensor readings, apply or train an anomaly-detection model, and generate alerts for unusual patterns. This is a project direction that would tie my three interests together. Nothing has been built yet, so there are no datasets or results.

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:22D3EE,100:8B5CF6&height=2" width="100%" alt="" />
</p>

## Technical Toolkit

Tools I have studied or used while learning. This is a list of exposure, not claims of professional mastery.

**Cybersecurity & Networking**

<img src="https://img.shields.io/badge/Linux-0D1117?style=flat-square&logo=linux&logoColor=22D3EE" alt="Linux" />
<img src="https://img.shields.io/badge/Kali%20Linux-0D1117?style=flat-square&logo=kalilinux&logoColor=22D3EE" alt="Kali Linux" />
<img src="https://img.shields.io/badge/Nmap-0D1117?style=flat-square&logoColor=22D3EE" alt="Nmap" />
<img src="https://img.shields.io/badge/Burp%20Suite-0D1117?style=flat-square&logo=burpsuite&logoColor=22D3EE" alt="Burp Suite" />
<img src="https://img.shields.io/badge/Networking-0D1117?style=flat-square&logoColor=22D3EE" alt="Networking" />

**IoT & Embedded Systems**

<img src="https://img.shields.io/badge/ESP32-0D1117?style=flat-square&logo=espressif&logoColor=8B5CF6" alt="ESP32" />
<img src="https://img.shields.io/badge/Arduino-0D1117?style=flat-square&logo=arduino&logoColor=8B5CF6" alt="Arduino" />

**Programming & Automation**

<img src="https://img.shields.io/badge/Python-0D1117?style=flat-square&logo=python&logoColor=22D3EE" alt="Python" />
<img src="https://img.shields.io/badge/C-0D1117?style=flat-square&logo=c&logoColor=22D3EE" alt="C" />
<img src="https://img.shields.io/badge/C%2B%2B-0D1117?style=flat-square&logo=cplusplus&logoColor=22D3EE" alt="C++" />
<img src="https://img.shields.io/badge/Git-0D1117?style=flat-square&logo=git&logoColor=22D3EE" alt="Git" />
<img src="https://img.shields.io/badge/n8n-0D1117?style=flat-square&logo=n8n&logoColor=22D3EE" alt="n8n" />

**Applied AI: Currently Exploring** &nbsp;<sub>(learning and prototyping, not model training or production ML)</sub>

<img src="https://img.shields.io/badge/LLM%20integrations-0D1117?style=flat-square&logoColor=8B5CF6" alt="LLM integrations" />
<img src="https://img.shields.io/badge/AI--assisted%20workflows-0D1117?style=flat-square&logoColor=8B5CF6" alt="AI-assisted workflows" />
<img src="https://img.shields.io/badge/AI%20%2B%20IoT%20concepts-0D1117?style=flat-square&logoColor=8B5CF6" alt="AI + IoT concepts" />
<img src="https://img.shields.io/badge/API%20orchestration-0D1117?style=flat-square&logoColor=8B5CF6" alt="API orchestration" />

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:22D3EE,100:8B5CF6&height=2" width="100%" alt="" />
</p>

## Achievements

| | |
|---|---|
| 🥇 | **First place**, Tech Tonic hackathon, with the **FoodLink** project |
| 🎯 | IoT concept selected for the **Round-II budget-negotiation stage**, CHARUSAT SSIP Pitching 2026-27 |
| 🛠️ | Participated in the **Odoo hackathon at IIT Gandhinagar** |
| ⏱️ | Completed the **12-hour Hack Baroda hackathon** |

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:22D3EE,100:8B5CF6&height=2" width="100%" alt="" />
</p>

## GitHub Activity

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Aaryan1809&show_icons=true&theme=tokyonight&hide_border=true" alt="Aaryan1809 GitHub stats" />
  <img height="165" src="https://streak-stats.demolab.com?user=Aaryan1809&theme=tokyonight&hide_border=true" alt="Aaryan1809 GitHub streak" />
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:22D3EE,100:8B5CF6&height=2" width="100%" alt="" />
</p>

<p align="center">
  <i>Test carefully. Build deliberately. Document honestly.</i>
</p>

<p align="center">
  <sub>Cybersecurity • Embedded Systems • Applied AI</sub>
</p>
```
