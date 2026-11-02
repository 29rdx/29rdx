# Rupraj Datta

<p align="left">
  <strong>Software &amp; Systems Engineer</strong> • <strong>Application Security &amp; Distributed Infrastructure</strong><br>
  <em>B.Tech in Computer Science &amp; Engineering — Bennett University (Noida, India)</em>
</p>

[![Available for Hire](https://img.shields.io/badge/Status-Actively_Seeking_Internships_%26_SWE_Roles-2ea44f?style=flat-square&logo=github)](mailto:dattarupraj@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-dattarupraj-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dattarupraj)
[![Email](https://img.shields.io/badge/Email-dattarupraj@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:dattarupraj@gmail.com)
[![X](https://img.shields.io/badge/X-@Rupraj29-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/Rupraj29)

> **🎯 Executive Objective**: Actively seeking **Software Engineering Internships** and **Early Career Systems / Backend / AppSec Roles** (2026/2027). Focused on high-concurrency architectures, network packet inspection (DPI), OWASP API security hardening, and resilient distributed protocols. Open to on-site, hybrid, or remote opportunities globally.

---



## 🌐 Verified Merged Open-Source Upstream Contributions

Direct production code contributions reviewed and merged into external open-source ecosystems:

* **[calibrain/shelfmark #1632](https://github.com/calibrain/shelfmark/pull/1632)** [![Merged](https://img.shields.io/badge/PR_1632-MERGED-8957e5?style=flat-square&logo=git&logoColor=white)](https://github.com/calibrain/shelfmark/pull/1632)  
  *High-Throughput Spooled Disk Buffering*: Re-engineered memory buffering for heavy debrid streaming pipelines using disk-backed spooled temporary file buffers, eliminating out-of-memory crashes on resource-constrained servers. Collaborated with upstream maintainers on stream cancellation disposal and regression tests. **Merged into upstream master.**

* **[nikhilrai-tech/Nigrani #45](https://github.com/nikhilrai-tech/Nigrani/pull/45)** [![Merged](https://img.shields.io/badge/PR_45-MERGED-8957e5?style=flat-square&logo=git&logoColor=white)](https://github.com/nikhilrai-tech/Nigrani/pull/45)  
  *Fractional Telemetry & Metric Scaling Engine*: Implemented dynamic ratio unit scaling (`unit: ratio`) for system metrics, unified telemetry chart scaling, and authored full frontend/backend regression suites with all 230 tests passing. **Merged into upstream main.**

* **[nikhilrai-tech/Nigrani #48](https://github.com/nikhilrai-tech/Nigrani/pull/48)** [![Open PR](https://img.shields.io/badge/PR_48-OPEN-2ea44f?style=flat-square&logo=git&logoColor=white)](https://github.com/nikhilrai-tech/Nigrani/pull/48)  
  *In-Cluster Kubernetes Deployment Bundle*: Authored full Kubernetes deployment suite under `examples/kubernetes-deploy.yaml` (Deployment, ClusterIP Service, ConfigMap with auto serviceAccount/CA discovery, and Secret) addressing Issue #44.

* **[AaronCreor/PyFuncAI #6](https://github.com/AaronCreor/PyFuncAI/pull/6)** [![Merged](https://img.shields.io/badge/PR_6-MERGED-8957e5?style=flat-square&logo=git&logoColor=white)](https://github.com/AaronCreor/PyFuncAI/pull/6)  
  *Structured Cache Metadata Validation*: Implemented structured JSON metadata extraction and validation for offline AI caching environments, backed by comprehensive unit test coverage. **Merged into upstream master.**

* **[OWASP/CheatSheetSeries #2892](https://github.com/OWASP/CheatSheetSeries/pull/2892)** [![Under Review](https://img.shields.io/badge/PR_2892-UNDER_REVIEW-e3b341?style=flat-square&logo=git&logoColor=white)](https://github.com/OWASP/CheatSheetSeries/pull/2892)  
  *XSS Filter Evasion Security Normalization*: Addressed OWASP tracking issue #2792 by removing legacy server-side execution vectors (SSI/PHP) from client-side XSS filter evasion docs and standardizing payload syntax across security consoles.

---

## 🚀 Flagship Systems & Cybersecurity Repositories

| Repository | Domain & Architecture | Core Highlights & Tech Stack | Validation |
| :--- | :--- | :--- | :---: |
| **[🛡️ Backend Security Sentinel](https://github.com/29rdx/backend-security-sentinel)** | **OWASP API Vulnerability Scanner** | Automated auditor targeting OWASP API Top 10 risks: BOLA authorization bypass, SSRF cloud metadata filtering (`169.254.169.254`), JWT key confusion (`alg: none`), and Shannon entropy secret extraction. <br>`Python` `OWASP` `DevSecOps` `FastAPI` | ![Passing](https://img.shields.io/badge/17_Suites-Passing-2ea44f?style=flat-square) |
| **[🛡️ Sentinel DPI Engine](https://github.com/29rdx/sentinel-dpi-engine)** | **High-Throughput Deep Packet Inspection** | C++17 wire-rate packet dissection engine: 802.1Q VLAN tag parsing, IPv6 extension headers, lock-free ring buffers, JA3 TLS Client Hello fingerprinter, and DNS entropy covert-channel detection. <br>`C++17` `Network Security` `DPI` `PCAP` | ![Passing](https://img.shields.io/badge/C%2B%2B17-Verified-2ea44f?style=flat-square) |
| **[🛡️ CVE Analysis Vault](https://github.com/29rdx/cve-analysis-vault)** | **Vulnerability Research & Test Harnesses** | In-depth root-cause autopsies and safe test harnesses: CVE-2024-3094 (XZ IFUNC backdoor ELF scanner & YARA signatures), CVE-2023-4863 (libwebp Huffman heap overflow), and CVE-2023-44487 (HTTP/2 Rapid Reset). <br>`Python` `C++17` `AppSec` `Exploit Research` | ![Passing](https://img.shields.io/badge/Harnesses-Passing-2ea44f?style=flat-square) |
| **[🛡️ Aegis Mesh Pay](https://github.com/29rdx/aegis-mesh-pay)** | **Zero-Connectivity Offline Payments** | Resilient offline payment gateway: Offline UPI, RSA-2048 + AES-GCM signed transaction vouchers, BLE binary mesh transport, SHA-256 Merkle tree ledger, and Bloom filter double-spend prevention. <br>`Java 17` `Spring Boot` `Cryptography` `Zero-Trust` | ![Passing](https://img.shields.io/badge/Maven_Test-Passing-2ea44f?style=flat-square) |
| **[⚡ Distributed Telemetry Engine](https://github.com/29rdx/distributed-telemetry-engine)** | **Streaming Observability Pipeline** | High-concurrency telemetry ingestion engine: lock-free atomic CAS circular ring buffer, error-preserving tail sampler, reservoir P50/P90/P99 latency percentile estimator, and OpenTelemetry OTLP exporter. <br>`Go 1.22` `Observability` `Distributed Systems` | ![Passing](https://img.shields.io/badge/Go_Test-Verified-2ea44f?style=flat-square) |

---

## 🏆 Engineering Leadership

### **Team Head & Lead Architect — Team Nakshatra-X**
*Smart India Hackathon (SIH 2026) • Ministry of Steel & MOIL Limited*  
`Next.js 16` `TypeScript` `Three.js` `React Globe GL` `Supabase` `PostgreSQL` `STAC Sentinel-2`

- **SIH Qualifier**: Successfully led Team Nakshatra-X through competitive university selection rounds for the Smart India Hackathon.
- **Client & Problem**: Architected an orbital geospatial intelligence and sub-surface manganese prospectivity mapping platform for MOIL Limited.
- **Architecture**: Directed full-stack development, implementing interactive 3D Earth telemetry (`Three.js`), live mission control dashboards, and automated ESA Sentinel-2 spectral band-ratio processing pipelines.
- **Repository**: [github.com/29rdx/newNakshatra-x](https://github.com/29rdx/newNakshatra-x)

---

## 🛠️ Technical Competencies

- **Languages:** C++17/20, Python, Go, Java 17, TypeScript, SQL, Bash
- **Systems & Architecture:** Deep Packet Inspection (DPI), Lock-Free Ring Buffers, High-Concurrency APIs, Streaming Telemetry, Microservices
- **Cybersecurity & Cryptography:** OWASP API Top 10, Zero-Trust Architecture, RSA-2048 / AES-GCM, Merkle Proofs, YARA Rule Authoring, Vulnerability Analysis
- **Infrastructure & Tools:** Docker, Linux / POSIX APIs, GitHub Actions CI/CD, CMake, PostgreSQL, Supabase, Git

---

## 📬 Contact & Connect

- 📧 **Direct Email:** [dattarupraj@gmail.com](mailto:dattarupraj@gmail.com)
- 💼 **LinkedIn:** [linkedin.com/in/dattarupraj](https://www.linkedin.com/in/dattarupraj)
- 💻 **GitHub:** [github.com/29rdx](https://github.com/29rdx?tab=repositories)
- 📍 **Location:** Noida, Uttar Pradesh, India
