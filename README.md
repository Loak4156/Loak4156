<p align="center">
  <img src="assets/profile-header.svg" width="100%" alt="VD - Threat Intelligence Lead. Turning fragmented signals into actionable intelligence." />
</p>

<p align="center">
  <strong>Threat Intelligence Lead @ CYBEROO</strong><br />
  <sub>Threat research · Intelligence operations · LLM-assisted tooling</sub>
</p>

<p align="center">
  <a href="#about">About</a> &nbsp; / &nbsp;
  <a href="#focus">Focus</a> &nbsp; / &nbsp;
  <a href="#selected-projects">Projects</a> &nbsp; / &nbsp;
  <a href="#toolkit">Toolkit</a> &nbsp; / &nbsp;
  <a href="#credentials">Credentials</a> &nbsp; / &nbsp;
  <a href="https://www.linkedin.com/in/kononow/">LinkedIn</a>
</p>

---

## About

I connect **threat research, intelligence operations, and practical automation** to help analysts make better decisions. My work spans ransomware, dark web intelligence, OSINT, and data breach analysis - with a particular focus on Russian-language open and closed sources.

With **6+ years in cybersecurity**, I have moved from leading SOC operations to building and operationalizing threat intelligence capabilities. Previously, I led a **20-analyst Tier 1 SOC team (2020-2024)**. That operational background shapes the tools I design: useful context, clear priorities, and workflows analysts can actually use.

I use **LLMs to turn my ideas and CTI requirements into working software**. My contribution is domain expertise, defining workflows, guiding development, and evaluating the results in practice.

<table>
<tr>
<td width="33%" valign="top">
<h3>01 / Investigate</h3>
Ransomware activity, dark web ecosystems, exposed data, and open-source signals. Connect the evidence to the threat.
</td>
<td width="33%" valign="top">
<h3>02 / Operationalize</h3>
Turn fragmented collection into enriched intelligence, asset-aware triage, and actionable analyst workflows.
</td>
<td width="33%" valign="top">
<h3>03 / Automate</h3>
Use LLMs to develop tools around real investigation needs. Define the requirements, guide implementation, and assess the results from an analyst’s perspective.
</td>
</tr>
</table>

## Focus

- **Ransomware & dark web intelligence** - track activity across leak sites, forums, and underground sources.
- **OSINT, SOCMINT & HUMINT** - bring technical signals and source context into the same investigation.
- **Exposure & breach analysis** - connect discovered data to affected assets and operational priorities.
- **LLM-assisted tooling** - translate CTI requirements into tools for collection, IOC extraction, deduplication, and alert triage.

## Selected projects

<sub>Private repositories. I define the requirements and workflows, guide development with LLMs, and evaluate the results in practice.</sub>

### 01 / CyberTI

**Threat Intelligence Operations Platform** · `Threat_Intel_Platform` · `Private`

A self-hosted CTI workspace that brings **dark web, ransomware leak sites, data breaches, forums, RSS, and social intelligence** into one operational workflow. It connects collected evidence to monitored assets and helps analysts review and prioritize findings.

**Capabilities:** IOC extraction and enrichment · Phishing domain monitoring · Credential exposure analysis · Asset correlation · Explainable risk scoring · Analyst triage

```text
  COLLECT                 CORRELATE                OPERATIONALIZE
  ───────                 ─────────                ──────────────
  Dark web & forums  ─┐
  Ransomware feeds   ─┼──▶ IOC extraction     ───▶ Asset-aware triage
  Breach signals    ─┤    Deduplication            Analyst review
  RSS & social      ─┘    Context enrichment       Response
```

Built around real CTI requirements: reduce repetitive work, preserve useful context, and help analysts move from a signal to a decision.

### 02 / Recon Control Center

**Reconnaissance & exposure analysis** · `recon-control-center` · `Private`

A web dashboard for investigating domains and IP addresses. It brings discovery, infrastructure context, and security checks into one place, with parallel tasks and live progress to reduce repetitive manual work.

**Capabilities:** Subdomain and DNS discovery · Infrastructure mapping · Web technology profiling · Service and TLS checks · Email security assessment · Exposure reporting

**My focus:** shaping a practical investigation workflow, selecting useful checks, and making findings easier to interpret.

### 03 / Hydra Fetch

**Multi-head Tor downloader** · `Hydra_Fetch` · `Private`

A purpose-built downloader for retrieving files from **Tor and onion services**, where slow routes, interrupted connections, and large archives make ordinary downloads difficult. It manages a configurable pool of Tor heads and coordinates multiple transfer streams through one local web interface.

**How it works**

- **Multi-head transfers** - distributes file segments across available Tor heads, downloading them concurrently when the source supports verified byte ranges.
- **Adaptive download modes** - tests the source before choosing parallel segments or a single stream. An optional race mode compares live streams, keeps the fastest, and stops redundant transfers within a traffic budget.
- **Validated assembly & resume** - checks file-version identifiers, byte ranges, and segment lengths before assembly. Preserves partial data after interruptions and resumes when the source confirms it is safe.
- **Access & session handling** - handles supported verification pages and allows user-assisted sign-in for protected downloads, with sessions kept locally.
- **Collection workflow** - combines batch queues, file discovery, multipart archive selection, live progress, and SHA-256 fingerprinting.

Designed to make collection over Tor more reliable and use available connections effectively. Actual throughput depends on Tor routes and the source service’s capacity.

**My contribution:** defining the collection requirements and multi-head workflow, guiding implementation with LLMs, and validating behavior in practical download scenarios.

## Toolkit

| Area | Tools & capabilities |
| :--- | :--- |
| **LLM-assisted development** | Requirements · Workflow design · AI coding tools · Practical validation |
| **Intelligence** | OSINT · SOCMINT · HUMINT · Dark web research · Threat hunting |
| **Analysis platforms** | Elasticsearch · Kibana · Siemplify |
| **Security tooling** | Nuclei · Invicti · Acunetix · Hashcat · Honeypots |
| **Infrastructure** | Docker · PostgreSQL · Debian · Ubuntu · Kali Linux · VMware · Hyper-V |
| **AI-assisted analysis** | LLM workflows · Collection enrichment · Analyst triage |

## Research & writing

- **Honeypot research** - deployed a research environment and analyzed attack telemetry with Elasticsearch and Kibana. The work contributed to the Cyberoo 2025 Observatory.
- **Published analysis** - contributions on threat intelligence, phishing, and dark web threats, with research featured in Cybersecurity360, CorCom, and La Repubblica.

[Explore my research and publications on LinkedIn](https://www.linkedin.com/in/kononow/)

**Languages:** Ukrainian · Italian · Russian · English

## Credentials

<p>
  <img src="https://img.shields.io/badge/IntelTechniques-OSIP-152c30?style=flat-square&amp;labelColor=101923&amp;color=286b59" alt="IntelTechniques OSIP" />
  <img src="https://img.shields.io/badge/CompTIA-CySA%2B-152c30?style=flat-square&amp;labelColor=101923&amp;color=286b59" alt="CompTIA CySA+" />
  <img src="https://img.shields.io/badge/Google_Siemplify-SCSA-152c30?style=flat-square&amp;labelColor=101923&amp;color=286b59" alt="Siemplify SCSA" />
</p>

<sub>IntelTechniques OSIP · CompTIA CySA+ · Siemplify SCSA</sub>

---

<p align="center">
  <strong>Better context. Clearer decisions. Stronger defense.</strong><br /><br />
  <sub>Ukrainian &amp; Italian citizen · Threat intelligence &amp; LLM-assisted tooling</sub>
</p>
