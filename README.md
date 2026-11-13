# Rupraj Datta

<p align="left">
  <strong>Backend Software Engineer &amp; Cybersecurity Specialist</strong><br>
  <em>High-Concurrency Systems • Application Security (AppSec) • Distributed Infrastructure</em><br>
  Bennett University — Greater Noida, India
</p>

[![GitHub](https://img.shields.io/badge/GitHub-29rdx-181717?style=flat-square&logo=github)](https://github.com/29rdx)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-dattarupraj-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dattarupraj)
[![Email](https://img.shields.io/badge/Email-dattarupraj@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:dattarupraj@gmail.com)
[![Status](https://img.shields.io/badge/Focus-Backend_%26_Security_Engineering-2ea44f?style=flat-square)](mailto:dattarupraj@gmail.com)

---

## ⚡ Engineering Impact: Problem → Solution → Proof

| Project / Ecosystem | Problem Addressed | Engineering Solution | Empirical Proof & Validation |
| :--- | :--- | :--- | :---: |
| **[🛡️ Backend Security Sentinel](https://github.com/29rdx/backend-security-sentinel)**<br>`Python` `FastAPI` `DevSecOps` | OWASP API Top 10 risks (BOLA, SSRF cloud metadata leaks, JWT key confusion) evade surface-level linters. | Built an automated AST & entropy-driven vulnerability scanner with Shannon entropy secret extraction and automated auth-header fuzzing. | ![Passing](https://img.shields.io/badge/41_Suites-Passing-2ea44f?style=flat-square)<br>Zero false-positive auth tests |
| **[🛡️ Sentinel DPI Engine](https://github.com/29rdx/sentinel-dpi-engine)**<br>`C++17` `CMake` `PCAP` `DPI` | Kernel-space packet processing causes high packet-drop rates under wire-rate throughput. | Architected a user-space C++17 packet dissector with lock-free ring buffers, 802.1Q VLAN parsing, JA3 TLS fingerprinter, and DNS covert entropy checks. | ![Passing](https://img.shields.io/badge/10_Subsystems-Passing-2ea44f?style=flat-square)<br>Deterministic CTest pass |
| **[🛡️ Aegis Mesh Pay](https://github.com/29rdx/aegis-mesh-pay)**<br>`Java 27` `Spring Boot` `Crypto` | Financial transactions in zero-connectivity / offline environments suffer from double-spending risks. | Implemented an offline payment gateway with RSA-2048 + AES-GCM signed vouchers, BLE binary mesh framing, and Bloom filter revocation lists. | ![Passing](https://img.shields.io/badge/7_Suites-Passing-2ea44f?style=flat-square)<br>All tests green in 4.2s |
| **[🐍 pallets/click #3914](https://github.com/pallets/click/issues/3914)**<br>`Python` `CLI Core` `PSF` | CLI runtime error hints silently omitted `auto_envvar_prefix` when required options were missing. | Surgically patched `Option.get_error_hint` to resolve context prefixes when `show_envvar=True`; added positive & negative test coverage. | ![Passing](https://img.shields.io/badge/2,623_Tests-Passing-2ea44f?style=flat-square)<br>[PR Compare Package](https://github.com/pallets/click/compare/main...29rdx:click:fix/3914-auto-envvar-error-hint?expand=1) |
| **[🐍 calibrain/shelfmark #1632](https://github.com/calibrain/shelfmark/pull/1632)**<br>`Python` `Systems` `Streaming` | Large debrid streaming downloads triggered out-of-memory (OOM) fatal crashes on constrained servers. | Re-engineered memory buffers to disk-backed `SpooledTemporaryFile` streaming pipelines with safe cancellation disposal. | ![Merged](https://img.shields.io/badge/PR_1632-Merged-8957e5?style=flat-square)<br>Merged into upstream master |
| **[🛰️ Team Nakshatra-X](https://github.com/29rdx/newNakshatra-x)**<br>`TypeScript` `Three.js` `GIS` | Sub-surface manganese exploration lacked real-time spectral telemetry processing for field mining teams. | Directed engineering for MOIL Limited (SIH 2026), building automated ESA Sentinel-2 band-ratio pipelines and interactive 3D Earth telemetry. | ![Qualified](https://img.shields.io/badge/SIH_2026-Qualified-2ea44f?style=flat-square)<br>Team Lead & Architect |

---

## 🌐 Verified Upstream Contributions

<!-- OSS-PRS:START -->

| Repository | Pull Request | Stack | Status | Date |
| :--- | :--- | :---: | :---: | :---: |
| 🐍 **[calibrain/shelfmark](https://github.com/calibrain/shelfmark)** | **[Spool large debrid downloads to disk](https://github.com/calibrain/shelfmark/pull/1632)** | `🐍 Python` | 🟣 **Merged** | Nov 2026 |
| 🐍 **[AaronCreor/PyFuncAI](https://github.com/AaronCreor/PyFuncAI)** | **[Add JSON metadata output to cache list](https://github.com/AaronCreor/PyFuncAI/pull/6)** | `🐍 Python` | 🟣 **Merged** | Nov 2026 |
| 🐍 **[nikhilrai-tech/Nigrani](https://github.com/nikhilrai-tech/Nigrani)** | **[Add ratio unit for fractional metrics](https://github.com/nikhilrai-tech/Nigrani/pull/45)** | `🐍 Python` | 🟣 **Merged** | Nov 2026 |
| **[firstcontributions/first-contributions](https://github.com/firstcontributions/first-contributions)** | [Add Rupraj Datta to Contributors](https://github.com/firstcontributions/first-contributions/pull/127760) | `Multi-Stack` | 🟣 **Merged** | Nov 2026 |
| **[OWASP/CheatSheetSeries](https://github.com/OWASP/CheatSheetSeries)** | [docs(xss): normalize quotes and apostrophe in WAF bypass strings (#2792)](https://github.com/OWASP/CheatSheetSeries/pull/2918) | `JavaScript` | 🟣 **Merged** | Nov 2026 |

<!-- OSS-PRS:END -->

---

## 🛠️ Core Technical Competencies

- **Languages:** Python (3.9 - 3.14), C++17/20, Java (17 / 27), Go, SQL, Bash
- **Backend & Systems:** Deep Packet Inspection (DPI), High-Concurrency APIs, Lock-Free Data Structures, Streaming Telemetry, Microservices
- **Security & Cryptography:** OWASP API Top 10, Zero-Trust Architecture, RSA-2048 / AES-GCM, Merkle Proofs, YARA Rule Authoring, Exploit Autopsies
- **Tooling & Infrastructure:** Linux / POSIX APIs, Git (Worktrees), Docker, GitHub Actions CI/CD, CMake, Maven, Pytest

---

## 📬 Contact & Connect

- 📧 **Email:** [dattarupraj@gmail.com](mailto:dattarupraj@gmail.com)
- 💼 **LinkedIn:** [linkedin.com/in/dattarupraj](https://www.linkedin.com/in/dattarupraj)
- 💻 **GitHub:** [github.com/29rdx](https://github.com/29rdx)
- 📍 **Location:** Greater Noida, India
