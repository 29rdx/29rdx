# Rupraj Datta

<p align="left">
  <strong>Software &amp; Systems Engineer</strong> • <strong>Application Security &amp; Distributed Infrastructure</strong><br>
  <em>B.Tech in Computer Science &amp; Engineering — Bennett University (Greater Noida, India)</em>
</p>

[![GSoC 2027 Aspirant](https://img.shields.io/badge/GSoC_2027-Contributor_Preparation-2ea44f?style=flat-square&logo=google)](https://summerofcode.withgoogle.com/)
[![GitHub](https://img.shields.io/badge/GitHub-29rdx-181717?style=flat-square&logo=github)](https://github.com/29rdx)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-dattarupraj-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dattarupraj)
[![Email](https://img.shields.io/badge/Email-dattarupraj@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:dattarupraj@gmail.com)
[![X](https://img.shields.io/badge/X-@Rupraj29-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/Rupraj29)

> **🎯 Engineering Focus & GSoC 2027 Objective**: Aspiring **Google Summer of Code 2027** contributor specializing in **Application Security, DevSecOps, Python Systems, and Distributed Infrastructure**. Committed to rigorous open-source engineering: isolated worktree development, test-driven defect reproduction, surgical minimal patches, and peer-reviewed upstream collaboration. Actively engaging with **OWASP Foundation**, **Python Software Foundation (PSF)** ecosystem, and **Jenkins / CDF**.

---

## 🏛️ GSoC 2027 Target Communities & Specializations

| Organization / Community | Engineering Domain & Track | Relevant Projects & Upstream Focus | Contributor Status |
| :--- | :--- | :--- | :---: |
| **🛡️ OWASP Foundation** | Application Security & Scanner Tooling | **[CheatSheetSeries](https://github.com/OWASP/CheatSheetSeries)**, **[Nettacker](https://github.com/OWASP/Nettacker)**<br>• XSS WAF bypass syntax normalization<br>• High-precision HTTP response timing (`time.perf_counter`) | Merged & In-Flight |
| **🐍 Python Software Foundation** | Core CLI Runtime & Environment Mechanics | **[pallets/click](https://github.com/pallets/click)**<br>• Option error hint resolution for auto-derived environment variables (#3914)<br>• Comprehensive regression testing (2,623 unit tests verified) | Packaged Patch |
| **⚙️ Jenkins / CDF** | CI/CD Infrastructure & Systems Tooling | **[jenkinsci/jenkins](https://github.com/jenkinsci/jenkins)**<br>• Java backend performance, pipeline resilience, and plugin modernization | Research & Lab Prep |

---

## 🌐 Open-Source Upstream Contributions

### Verified Merged Upstream PRs

<!-- OSS-PRS:START -->

| Repository | Pull Request | Stack | Status | Date |
| :--- | :--- | :---: | :---: | :---: |
| 🐍 **[calibrain/shelfmark](https://github.com/calibrain/shelfmark)** | **[Spool large debrid downloads to disk](https://github.com/calibrain/shelfmark/pull/1632)** | `🐍 Python` | 🟣 **Merged** | Nov 2026 |
| 🐍 **[AaronCreor/PyFuncAI](https://github.com/AaronCreor/PyFuncAI)** | **[Add JSON metadata output to cache list](https://github.com/AaronCreor/PyFuncAI/pull/6)** | `🐍 Python` | 🟣 **Merged** | Nov 2026 |
| 🐍 **[nikhilrai-tech/Nigrani](https://github.com/nikhilrai-tech/Nigrani)** | **[Add ratio unit for fractional metrics](https://github.com/nikhilrai-tech/Nigrani/pull/45)** | `🐍 Python` | 🟣 **Merged** | Nov 2026 |
| **[firstcontributions/first-contributions](https://github.com/firstcontributions/first-contributions)** | [Add Rupraj Datta to Contributors](https://github.com/firstcontributions/first-contributions/pull/127760) | `Multi-Stack` | 🟣 **Merged** | Nov 2026 |
| **[OWASP/CheatSheetSeries](https://github.com/OWASP/CheatSheetSeries)** | [docs(xss): normalize quotes and apostrophe in WAF bypass strings (#2792)](https://github.com/OWASP/CheatSheetSeries/pull/2918) | `JavaScript` | 🟣 **Merged** | Nov 2026 |

<!-- OSS-PRS:END -->

### Active Upstream Patches & Investigations

| Target Repository | Issue / Topic | Technical Solution | Validation & Safety | Status |
| :--- | :--- | :--- | :--- | :---: |
| **[pallets/click](https://github.com/pallets/click)** | **[Issue #3914](https://github.com/pallets/click/issues/3914)**: Missing option hint omits `auto_envvar_prefix` | Patched `Option.get_error_hint` to derive context prefix when `show_envvar=True`; added positive & negative tests. | **2,623 passed, 0 failures**<br>Signed-off commit `d881278` | [Compare & Review](https://github.com/pallets/click/compare/main...29rdx:click:fix/3914-auto-envvar-error-hint?expand=1) |
| **[OWASP/Nettacker](https://github.com/OWASP/Nettacker)** | **[Issue #1859](https://github.com/OWASP/Nettacker/issues/1859)**: Clock skew in HTTP duration calculation | Migrated wall-clock `time.time()` to monotonic `time.perf_counter()` across scanner engine. | **11/11 unit tests passed**<br>Isolated worktree verified | Awaiting Assignment |

---

## 🚀 Flagship Systems & Cybersecurity Projects

| Repository | Architecture & Engineering Focus | Highlights & Tech Stack | Verification & Tests |
| :--- | :--- | :--- | :---: |
| **[🛡️ Backend Security Sentinel](https://github.com/29rdx/backend-security-sentinel)** | **OWASP API Vulnerability Scanner** | Automated security auditor targeting OWASP API Top 10 risks: BOLA authorization bypass, SSRF cloud metadata filtering (`169.254.169.254`), JWT key confusion (`alg: none`), and Shannon entropy secret extraction. <br>`Python 3.9+` `FastAPI` `pytest` `DevSecOps` | ![Passing](https://img.shields.io/badge/41_Suites-Passing-2ea44f?style=flat-square) |
| **[🛡️ Sentinel DPI Engine](https://github.com/29rdx/sentinel-dpi-engine)** | **Wire-Rate Deep Packet Inspection** | High-throughput C++17 packet dissection engine: 802.1Q VLAN parsing, IPv6 extension headers, lock-free ring buffers, JA3 TLS Client Hello fingerprinter, and DNS entropy covert-channel detection. <br>`C++17` `CMake` `Network Security` `PCAP` | ![Passing](https://img.shields.io/badge/CTest_10_Subsystems-Passing-2ea44f?style=flat-square) |
| **[🛡️ CVE Analysis Vault](https://github.com/29rdx/cve-analysis-vault)** | **Vulnerability Research & Test Harnesses** | In-depth root-cause autopsies and safe test harnesses: CVE-2024-3094 (XZ IFUNC backdoor ELF scanner & YARA signatures), CVE-2023-4863 (libwebp Huffman heap overflow), and CVE-2023-44487 (HTTP/2 Rapid Reset). <br>`Python` `C++17` `AppSec` `Exploit Research` | ![Passing](https://img.shields.io/badge/6_Suites-Passing-2ea44f?style=flat-square) |
| **[🛡️ Aegis Mesh Pay](https://github.com/29rdx/aegis-mesh-pay)** | **Zero-Connectivity Offline Payments** | Resilient offline payment gateway: Offline UPI, RSA-2048 + AES-GCM signed transaction vouchers, BLE binary mesh transport, SHA-256 Merkle tree ledger, and Bloom filter double-spend prevention. <br>`Java 27` `Spring Boot 3.3.4` `Cryptography` `Zero-Trust` | ![Passing](https://img.shields.io/badge/Maven_Test-Passing-2ea44f?style=flat-square) |
| **[🛰️ Nakshatra-X 3D Platform](https://github.com/29rdx/newNakshatra-x)** | **Geospatial Intelligence & Telemetry** | Interactive orbital 3D telemetry visualization, live mission control dashboard, and automated ESA Sentinel-2 spectral band-ratio processing pipelines built for MOIL Limited. <br>`JavaScript` `HTML5` `CSS3` `Three.js` `REST APIs` | ![Passing](https://img.shields.io/badge/SIH_2026-Qualified-2ea44f?style=flat-square) |

---

## 🏆 Engineering Leadership

### **Team Head & Lead Architect — Team Nakshatra-X**
*Smart India Hackathon (SIH 2026) • Ministry of Steel & MOIL Limited*  
`JavaScript` `HTML5` `CSS3` `Three.js` `REST APIs` `STAC Sentinel-2`

- **SIH Qualifier**: Led Team Nakshatra-X through competitive university evaluation rounds for the national Smart India Hackathon.
- **Client & Problem**: Architected an orbital geospatial intelligence and sub-surface manganese prospectivity mapping platform for MOIL Limited.
- **Architecture**: Directed full-stack development, implementing interactive 3D Earth telemetry (`Three.js`), live mission control dashboards, and automated ESA Sentinel-2 spectral band-ratio processing pipelines.
- **Repository**: [github.com/29rdx/newNakshatra-x](https://github.com/29rdx/newNakshatra-x)

---

## 🔬 Open-Source Engineering Discipline & Standards

Every contribution follows a strict, repeatable engineering lifecycle:

```text
[Upstream Issue Discovery]
       │
       ▼
[Policy & Contributor Check] ──► (Verify organization AI & contribution guidelines)
       │
       ▼
[Isolated Git Worktree]      ──► (/tmp/oss-workspace/<repo>/<issue>/)
       │
       ▼
[Baseline Test Suite]        ──► (Confirm existing tests pass on pristine upstream)
       │
       ▼
[Failing Defect Reproduction]──► (Author deterministic reproduction script / unit test)
       │
       ▼
[Surgical Minimal Patch]     ──► (Minimal diff, preserve backwards compatibility)
       │
       ▼
[Full Regression Suite]      ──► (Run complete project test suite; 0 regressions)
       │
       ▼
[Documentation & Changelog]  ──► (Update CHANGES.md, docstrings, release notes)
       │
       ▼
[DCO Sign-off & Human Gate]  ──► (Signed-off-by: Rupraj Datta <dattarupraj@gmail.com>)
```

- **Zero Commit Gaming:** No synthetic commits, no artificial streak scripts, no vanity metrics.
- **Human Comprehension Gate:** Every line of submitted code must be thoroughly understood, defensible in technical review, and covered by automated tests.
- **DCO & Licensing:** Strict adherence to Developer Certificate of Origin (DCO), MIT/Apache-2.0 licenses, and community codes of conduct.

---

## 🛠️ Technical Competencies

- **Languages:** Python (3.9 - 3.14), Java (17 / 27), C++17/20, Go, JavaScript / TypeScript, SQL, Bash
- **Systems & Architecture:** Deep Packet Inspection (DPI), Lock-Free Ring Buffers, High-Concurrency Web APIs, Streaming Telemetry, Microservices
- **Cybersecurity & Cryptography:** OWASP Top 10 / API Security, Zero-Trust Architecture, RSA-2048 / AES-GCM, Merkle Proofs, YARA Rule Authoring, Vulnerability Analysis
- **Frameworks & Runtimes:** Spring Boot 3, FastAPI, Node.js, Three.js, CMake, JUnit 5, Pytest
- **Infrastructure & Quality:** Linux / POSIX APIs, Git (Worktrees, Submodules), GitHub Actions CI/CD, Docker, Maven, CTest

---

## 📬 Contact & Connect

- 📧 **Direct Email:** [dattarupraj@gmail.com](mailto:dattarupraj@gmail.com)
- 💼 **LinkedIn:** [linkedin.com/in/dattarupraj](https://www.linkedin.com/in/dattarupraj)
- 💻 **GitHub:** [github.com/29rdx](https://github.com/29rdx?tab=repositories)
- 📍 **Location:** Greater Noida, Uttar Pradesh, India
