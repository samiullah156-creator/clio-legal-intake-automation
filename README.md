<!-- styled:v2 -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1d1726,50:167dfe,100:9533fa&height=180&section=header&text=Clio%20Legal%20Intake%20%26%20Matter%20Automation&fontSize=31&fontColor=ffffff&fontAlignY=36&desc=Case%20study%20%E2%80%A2%20Legal%20%E2%80%A2%20Python%20API%20and%20n8n&descAlignY=58&descSize=16&animation=fadeIn" width="100%" alt="Clio Legal Intake & Matter Automation" />

**An AI agent qualifies every new inquiry, checks conflicts and opens the contact and matter in Clio with no manual data entry.**

<p>
  <img src="https://img.shields.io/badge/Legal-167dfe?style=flat-square" alt="Legal" />
  <img src="https://img.shields.io/badge/Python%20API%20and%20n8n-9533fa?style=flat-square" alt="Python API and n8n" />
  <img src="https://img.shields.io/badge/Python-231f20?style=flat-square" alt="Python" />
  <img src="https://img.shields.io/badge/Clio%20API-231f20?style=flat-square" alt="Clio API" />
  <img src="https://img.shields.io/badge/n8n-231f20?style=flat-square" alt="n8n" />
  <img src="https://img.shields.io/badge/OpenAI-231f20?style=flat-square" alt="OpenAI" />
  <img src="https://img.shields.io/badge/AI%20Agents-231f20?style=flat-square" alt="AI Agents" />
  <img src="https://img.shields.io/badge/Gmail-231f20?style=flat-square" alt="Gmail" />
</p>

<p>
  <a href="#overview">Overview</a> ·
  <a href="#key-features">Key features</a> ·
  <a href="#results">Results</a> ·
  <a href="#tech-stack">Tech stack</a>
</p>

</div>

---

![Clio legal intake workflow in n8n: intake webhook, AI agent with conflict check, then Clio contact, matter, consult link and attorney alert.](assets/cover.webp)

## Overview

New client inquiries from web forms and email had to be entered into Clio by hand, which slowed intake. Lexvaxa built a custom Python service on the Clio API, orchestrated with n8n. An AI agent qualifies each inquiry and extracts the case details, runs a conflict check against Clio contacts, creates the contact and matter in Clio, assigns tasks and sends a consultation link. The client gets a welcome email and the attorney gets an alert; unqualified inquiries receive a polite decline. Screens shown use sample data, so no client records are exposed.

## The challenge

Manual data entry into Clio delayed responses to new inquiries and left room for errors.

## The solution

A Python Clio API service and an n8n workflow with an OpenAI agent, memory and a conflict check tool that routes qualified leads into Clio automatically.

## Key features

- AI qualification of every inquiry
- Case details extracted from forms and emails
- Conflict check against Clio contacts
- Clio contact and matter created automatically
- Tasks assigned and consultation booked
- Welcome email to the client and alert to the attorney
- Polite decline for unqualified inquiries

## Results

- Intake moves from first contact to an open Clio matter with no manual data entry

## Tech stack

![Python](https://img.shields.io/badge/Python-1d1726?style=for-the-badge) ![Clio API](https://img.shields.io/badge/Clio%20API-1d1726?style=for-the-badge) ![n8n](https://img.shields.io/badge/n8n-1d1726?style=for-the-badge) ![OpenAI](https://img.shields.io/badge/OpenAI-1d1726?style=for-the-badge) ![AI Agents](https://img.shields.io/badge/AI%20Agents-1d1726?style=for-the-badge) ![Gmail](https://img.shields.io/badge/Gmail-1d1726?style=for-the-badge)

## Privacy

Client names and records are confidential. Every screen in this repository uses sample data, and source code that belongs to the client is not published.

## Links

- Case study on Lexvaxa: https://lexvaxa.com/work/clio-legal-intake-automation

---

<div align="center">

**Built by [Ch Muhammad Samiullah](https://github.com/samiullah156-creator)** · AI Automation Engineer and Full-Stack Developer at [Lexvaxa](https://lexvaxa.com)

<a href="https://github.com/samiullah156-creator"><img src="https://img.shields.io/badge/More%20projects-181717?style=for-the-badge&logo=github&logoColor=white" alt="More projects" /></a>
<a href="https://lexvaxa.com/contact"><img src="https://img.shields.io/badge/Work%20with%20me-167dfe?style=for-the-badge&logo=googlecalendar&logoColor=white" alt="Work with me" /></a>
<a href="https://www.linkedin.com/in/sami-lexvaxa/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>

<sub>⭐ Star this repo if you found it useful</sub>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:9533fa,50:167dfe,100:1d1726&height=110&section=footer" width="100%" alt="" />
