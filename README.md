# 🛡️ Awesome SBOM Management Platform <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a><a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a><a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>

> 📦 A curated directory of top **SBOM Management Platforms**, Software Bill of Materials (SBOM) generators, continuous monitoring engines, vulnerability correlation tools, license compliance suites, and supply chain security stacks.

<p align="center">
  <img src="assets/banner.svg" alt="Awesome SBOM Management Banner" width="100%" />
</p>

This repository tracks notable **SaaS platforms** and **open-source projects** for **SBOM Management**. These tools generate, ingest, store, analyze, and continuously monitor Software Bills of Materials (SBOMs) in formats such as CycloneDX and SPDX, correlating components against vulnerability databases, enforcing policy, and supporting supply-chain transparency and compliance.

**Examples** include Anchore, Manifest Cyber, CycloneDX Platform, Dependency-Track, Mend.io, Black Duck, Chainguard, JFrog Xray, FOSSA, and Anchore Enterprise (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for SBOM generation, continuous component analysis, vulnerability scanning, and self-hosted management platforms — ideal for DevSecOps teams, platform engineers, and organizations seeking transparent, standards-based software supply chain security.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## 📑 Table of Contents
- [🏢 SaaS/Hosted Platforms](#-saashosted-platforms)
- [💻 Open-Source GitHub Projects](#-open-source-github-projects)
- [🛠️ How to Contribute](#-how-to-contribute)
- [⚠️ Disclaimer](#-disclaimer)

## 🏢 SaaS/Hosted Platforms

| Platform | Description/Features | Company Size (Valuation) | Pricing | Free Tier Limits |
| :--- | :--- | :--- | :--- | :--- |
| **[JFrog Xray](https://jfrog.com/xray/)** | Software composition analysis and security tool integrated with JFrog Artifactory that generates and analyzes SBOMs across artifacts and binaries. | ~ (Public Market Cap) | Starts at $150/month (Pro X tier) | 14-day free trial |
| **[Black Duck (Synopsys)](https://www.blackduck.com/)** | Enterprise SCA and open-source management platform providing deep component analysis, SBOM capabilities, license compliance, and governance controls. | ~.1B (Acquisition Valuation) | Starts at ~,000/year | 30-day free trial |
| **[Chainguard](https://www.chainguard.dev/)** | Secure container and supply-chain focused company offering hardened images, SBOMs, and provenance tooling for modern cloud-native environments. | ~.1B (Series C) | Starts at ~,000/year | Up to 5 container images |
| **[Mend.io](https://www.mend.io/)** | Application security and SCA platform with strong SBOM generation, vulnerability management, license compliance, and automated remediation features. | ~ (Acquisition Valuation) | Starts at ~/developer/year | Mend Renovate: 1 concurrent job, 15GB disk |
| **[Anchore](https://anchore.com/)** / **[Anchore Enterprise](https://anchore.com/)** | Leading software supply chain security platform offering SBOM generation (powered by Syft), policy enforcement, continuous monitoring, and enterprise management capabilities. | ~+ (Series B) | Starts at ~,500/year | 15-day free trial |
| **[FOSSA](https://fossa.com/)** | Open-source license compliance and vulnerability platform with robust SBOM generation, management, and audit-ready reporting. | ~+ (Series B) | Starts at ~,000/year | 5 projects, 25 developers limit |
| **[Manifest Cyber](https://www.manifestcyber.com/)** | Specialized SBOM and AIBOM management platform focused on automated supply-chain security, compliance, and visibility for regulated and critical industries. | ~+ (Seed/Series A) | Starts at ~,360/year | 0-day free trial (No free tier) |
| **[CycloneDX Platform](https://cyclonedx.org/)** | Ecosystem and commercial offerings built around the widely adopted CycloneDX SBOM standard for generation, validation, and exchange. | N/A (Open-Source Standard) | $0 (Open-Source Standard) | Unlimited (Free forever) |
| **[Dependency-Track](https://dependencytrack.org/)** | Intelligent component analysis platform (OWASP) that ingests SBOMs, continuously monitors for vulnerabilities and policy violations, and is available both as open source and managed offerings. | N/A (Open-Source Project) | $0 (Open-Source) | Unlimited (Free forever) |

## 💻 Open-Source GitHub Projects

- **[Trivy](https://github.com/aquasecurity/trivy)** [![Stars](https://img.shields.io/github/stars/aquasecurity/trivy?style=social&color=white)](https://github.com/aquasecurity/trivy/stargazers)  
  Popular all-in-one open-source scanner that produces CycloneDX/SPDX SBOMs and performs vulnerability, misconfiguration, and secret scanning.

- **[Grype](https://github.com/anchore/grype)** [![Stars](https://img.shields.io/github/stars/anchore/grype?style=social&color=white)](https://github.com/anchore/grype/stargazers)  
  Open-source vulnerability scanner that consumes SBOMs (or images/filesystems) and matches components against multiple vulnerability databases.

- **[OSV-Scanner](https://github.com/google/osv-scanner)** [![Stars](https://img.shields.io/github/stars/google/osv-scanner?style=social&color=white)](https://github.com/google/osv-scanner/stargazers)  
  Google’s open-source scanner that uses the OSV database and can work with SBOMs and lockfiles for vulnerability detection.

- **[OWASP Dependency-Check](https://github.com/jeremylong/DependencyCheck)** [![Stars](https://img.shields.io/github/stars/jeremylong/DependencyCheck?style=social&color=white)](https://github.com/jeremylong/DependencyCheck/stargazers)  
  Established open-source SCA tool that identifies project dependencies and checks them against known vulnerability databases.

- **[Syft](https://github.com/anchore/syft)** [![Stars](https://img.shields.io/github/stars/anchore/syft?style=social&color=white)](https://github.com/anchore/syft/stargazers)  
  Widely adopted open-source CLI and library from Anchore for generating high-quality SBOMs (CycloneDX, SPDX, and others) from container images, filesystems, and archives.

- **[Dependency-Track](https://github.com/DependencyTrack/dependency-track)** [![Stars](https://img.shields.io/github/stars/DependencyTrack/dependency-track?style=social&color=white)](https://github.com/DependencyTrack/dependency-track/stargazers)  
  OWASP flagship open-source platform for continuous SBOM ingestion, component inventory, vulnerability correlation, policy enforcement, and portfolio-wide risk visibility.

- **[Microsoft sbom-tool](https://github.com/microsoft/sbom-tool)** [![Stars](https://img.shields.io/github/stars/microsoft/sbom-tool?style=social&color=white)](https://github.com/microsoft/sbom-tool/stargazers)  
  Open-source tool for generating SPDX SBOMs, particularly useful in enterprise and Microsoft-centric build environments.

- **[Dagda](https://github.com/eliasgranderubio/dagda)** [![Stars](https://img.shields.io/github/stars/eliasgranderubio/dagda?style=social&color=white)](https://github.com/eliasgranderubio/dagda/stargazers)  
  A tool to perform static analysis of known vulnerabilities, trojans, viruses, malware & other malicious threats in docker images/containers.

- **[KubeClarity](https://github.com/openclarity/kubeclarity)** [![Stars](https://img.shields.io/github/stars/openclarity/kubeclarity?style=social&color=white)](https://github.com/openclarity/kubeclarity/stargazers)  
  KubeClarity is a tool for detection and management of Software Bill Of Materials (SBOM) and vulnerabilities of container images and filesystems.

- **[Tern](https://github.com/tern-tools/tern)** [![Stars](https://img.shields.io/github/stars/tern-tools/tern?style=social&color=white)](https://github.com/tern-tools/tern/stargazers)  
  Tern is a software composition analysis tool and SBOM generator for containers.

- **[cdxgen](https://github.com/CycloneDX/cdxgen)** [![Stars](https://img.shields.io/github/stars/CycloneDX/cdxgen?style=social&color=white)](https://github.com/CycloneDX/cdxgen/stargazers)  
  OWASP CycloneDX generator supporting a broad range of languages and build systems for native CycloneDX SBOM creation.

- **[Bomber](https://github.com/devops-kung-fu/bomber)** [![Stars](https://img.shields.io/github/stars/devops-kung-fu/bomber?style=social&color=white)](https://github.com/devops-kung-fu/bomber/stargazers)  
  Scans Software Bill of Materials (SBOMs) for security vulnerabilities.

- **[SPDX tools & utilities](https://github.com/spdx/tools)** [![Stars](https://img.shields.io/github/stars/spdx/tools?style=social&color=white)](https://github.com/spdx/tools/stargazers)  
  Official and community tooling for creating, validating, and working with SPDX-format SBOMs and license data.

- **[Hoppr](https://github.com/hoppr/hoppr)** [![Stars](https://img.shields.io/github/stars/hoppr/hoppr?style=social&color=white)](https://github.com/hoppr/hoppr/stargazers)  
  A framework for creating secure software supply chains and artifact bundles.

### ➕ Additional Strong Open-Source Options
- Harbor and other registry projects with SBOM storage and scanning integrations.
- in-toto / SLSA-related attestation and provenance tools that complement SBOMs.
- SBOM utility libraries for querying, diffing, and reporting on CycloneDX/SPDX documents.
- CI/CD plugins and GitHub Actions for automated SBOM generation and upload to Dependency-Track.
- VEX (Vulnerability Exploitability eXchange) tooling for richer risk context on top of SBOMs.

**Frameworks for building custom systems**: Generate SBOMs in CI with **Syft**, **Trivy**, or **cdxgen**, continuously monitor them in **Dependency-Track**, scan with **Grype** or **Trivy**, enforce policy via Dependency-Track’s expression engine or custom rules, and store signed attestations. Combine with open registries and local LLMs for natural-language risk summaries and remediation guidance.

## 🛠️ How to Contribute
1. Fork the repo.
2. Add/edit entries in README.md (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

⭐ Star the repo if you find it useful!

## ⚠️ Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- SBOM accuracy depends on the quality of generation tools, completeness of dependency detection, and timely vulnerability data. Always validate critical findings and maintain proper versioning and attestation practices.
- Self-hosted open-source platforms require ongoing maintenance of vulnerability feeds, infrastructure hardening, and access controls when handling sensitive software inventory data.

---
**Made for DevSecOps teams, platform engineers, security architects, and organizations building transparent software supply chains.**
Let's make SBOM management more open, continuous, and actionable.

## 📈 Star History
[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-SBOM-Management-Platform&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-SBOM-Management-Platform&type=date&legend=top-left)
