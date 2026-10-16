<p align="center">
  <img src="assets/banner.svg" alt="Awesome Certificate Management Banner" width="100%" />
</p>

# 🔐 Awesome Certificate Management

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Certificate-Management/stargazers"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Certificate-Management?style=social" alt="GitHub_Stars" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Certificate-Management/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Certificate-Management?style=social" alt="GitHub Forks" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Certificate-Management/issues"><img src="https://img.shields.io/github/issues/ishandutta2007/Awesome-Certificate-Management?style=flat-square" alt="Issues" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Certificate-Management/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ishandutta2007/Awesome-Certificate-Management?style=flat-square" alt="License" /></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

---

## 🌟 Top Certificate Management Ecosystem & Automated PKI Directory

> **A curated, battle-tested list of enterprise SaaS platforms and open-source GitHub projects for Certificate Lifecycle Management (CLM), ACME client automation (RFC 8555), private PKI authorities, Post-Quantum Cryptography (PQC), and cryptographic discovery.**

*Last updated: October 2026*

This repository indexes the premier **SaaS platforms** and **open-source repositories** powering modern **Machine Identity Management and Certificate Operations**. These tools enable DevOps teams, SREs, and security engineers to discover, issue, auto-renew, revoke, and monitor TLS/SSL, mTLS, SSH, and code-signing certificates across multi-cloud, on-premise, and Kubernetes estates.

---

## 📖 Table of Contents

- [📊 Sector Overview & Market Dynamics](#-sector-overview--market-dynamics)
- [☁️ SaaS / Hosted Platforms](#️-saas--hosted-platforms)
- [💻 Open-Source GitHub Projects](#-open-source-github-projects)
  - [Top Projects (Ranked by Stars)](#top-projects-ranked-by-stars)
  - [Enterprise Stacks & Specialized PKI Frameworks](#enterprise-stacks--specialized-pki-frameworks)
- [🤝 How to Contribute](#-how-to-contribute)
- [💖 Support & Sponsorship](#-support--sponsorship)
- [📈 Star History](#-star-history)
- [⚠️ Disclaimer & Architectural Insights](#️-disclaimer--architectural-insights)

---

## 📊 Sector Overview & Market Dynamics

The global **Certificate Lifecycle Management (CLM) and Machine Identity Security** market is estimated at **$1.8B – $2.2B in 2026** (with the broader digital certificate/PKI sector reaching over **$6.2B**), growing at a compound annual growth rate (**CAGR) of 14.5%–18.5%** toward **$11B+ by 2030**. 

The sector is **moderately fragmented with strong consolidation dynamics**, characterized by a bifurcated competitive landscape: hyperscale cloud providers (AWS, Microsoft Azure) capture universal commodity workloads, while a concentrated cohort of specialized enterprise security titans (CyberArk/Venafi, Keyfactor, DigiCert, Sectigo) battle for high-margin, complex multi-cloud and PQC cryptographic orchestration. As certificate validity spans contract toward 47 days and post-quantum cryptographic mandates loom, automation has evolved from an enterprise convenience into a non-negotiable operational prerequisite.

---

## ☁️ SaaS / Hosted Platforms

| Platform | Company Size (Valuation / Revenue) | Starting Tier Pricing | Free Tier Limits | Key Highlights |
| :--- | :--- | :--- | :--- | :--- |
| **[Azure Key Vault](https://azure.microsoft.com/en-us/products/key-vault/)** | **~$3.1 Trillion** market cap (Microsoft) / **$245B+** annual revenue | **$0.03** per 10,000 operations; **$3.00** per certificate auto-renewal | **Pay-as-you-go with $0 base fee**; certificate storage is free forever ($200 credit in 30-day Azure free account) | Integrated certificate management with Azure services, Managed HSM (FIPS 140-2 Level 3), Entra RBAC, and auto-rotation. |
| **[AWS Certificate Manager](https://aws.amazon.com/certificate-manager/)** | **~$2.0 Trillion** market cap (Amazon) / **$600B+** annual revenue | **$0.00** for public SSL/TLS certs on integrated services; Private CA starts at **$400/month** (or **$50/month** for short-lived mode) | **Unlimited free public SSL/TLS certs** provisioned on AWS services (ALB, CloudFront, API Gateway); **30-day free trial** for 1st Private CA | Automated generation, validation, and auto-renewal for AWS endpoints; ACM Private CA for enterprise internal PKI. |
| **[HashiCorp Vault](https://www.hashicorp.com/products/vault)** | **$6.4 Billion** acquisition enterprise value (IBM) | **$0.62/hour** (~**$45/month**) for HCP Vault Dedicated Dev cluster (single node, up to 25 clients) | **Self-hosted Vault Community Edition is free forever** (BSL 1.1 license); **$500 free trial credits** on HCP Vault | Secrets management with PKI secrets engine for dynamic internal CA, ACME support, and multi-cloud secrets automation. |
| **[DigiCert Trust Lifecycle Manager](https://www.digicert.com/)** | **~$8.0 Billion** valuation (Clearlake / TA Associates) | **~$7,900/year** baseline subscription for unified seat tiers (Essentials plan) | **No self-serve free tier** (custom guided enterprise demo / PoC available on request) | CLM with strong PQC research track record, deep CA integration, and unified seat management across domains and servers. |
| **[Venafi (CyberArk)](https://www.venafi.com/)** | **$1.54 Billion** acquisition price (CyberArk ARR: **~$150M**; CyberArk acquired for **$25B**) | **~$75,000/year** baseline entry contract tier for enterprise CLM | **30-day free trial** for TLS Protect Cloud / SaaS (enterprise on-premises TPP requires guided PoC) | Enterprise machine identity management, deep Windows/Active Directory support, TLS Protect, SSH Protect, and Firefly CA service. |
| **[Keyfactor](https://www.keyfactor.com/)** | **$1.3 Billion** valuation (Unicorn) / **$200M+** ARR | **~$50,000/year** base platform license (or hourly via AWS/Azure EJBCA Cloud pay-as-you-go) | **Open-source EJBCA Community is free forever**; **30-day free trial** on AWS/Azure Cloud marketplaces; timed Azure Test Drive for Command | Pragmatic enterprise CLM providing Keyfactor Command + EJBCA PKI, advanced PQC readiness, and migration tooling from Venafi. |
| **[Sectigo Certificate Manager](https://www.sectigo.com/)** | **$900 Million** acquisition valuation (GI Partners) / **~$90M+** revenue | **$25/month** (or **$250/year**) for SCM Pro starting tier | **30-day free trial** for Sectigo Certificate Manager (up to discovery and test certificate issuance limits) | Enterprise certificate lifecycle management, automated discovery, expiration monitoring, and cost-effective commercial CA integration. |
| **[Entrust Certificate Services](https://www.entrust.com/)** | **~$900 Million** annual revenue ($883M–$916M) | **$24 to $700+/year** for individual certs; enterprise platform subscriptions start at custom annual tiers | **No direct free tier for ECS platform** (60-day trial for adjacent Instant IDaaS; custom PoC sandbox via sales) | Enterprise certificate management with nCipher HSM integration, identity validation, and comprehensive PKI services. |
| **[GlobalSign Atlas](https://www.globalsign.com/)** | **~$160 Million** market cap (GMO GlobalSign Holdings TYO:3788 / ~¥22.5B–¥27B JPY) | **$199/year** baseline starting certificate packs (enterprise high-throughput Atlas CA via custom tiers) | **No self-serve free tier** (sales-assisted Proof of Concept / sandbox environment upon request) | High-throughput, cloud-based certificate management engine with automated issuance, ACME protocols, and Auto-Enrollment Gateway. |
| **[AppViewX](https://www.appviewx.com/)** | **~$100 Million** valuation / **~$100M–$133M** annual revenue (Haveli Investments) | **~$15,000/year** entry SaaS tier on AWS Marketplace private offers / pre-packaged CLM | **30-day free trial** for AVX ONE on AWS Marketplace; free container certificate tracking add-on for EKS | PKI and CLM with strong PQC readiness score, Cryptographic Bill of Materials generation, and cloud-delivered automation. |

---

## 💻 Open-Source GitHub Projects

All open-source projects are sorted in **descending order by GitHub_Stars_Count**. Each Stars_Badge links directly to the stargazers page of the repository.

### Top Projects (Ranked by Stars)

1. **[Caddy](https://github.com/caddyserver/caddy)** [![GitHub_Stars](https://img.shields.io/github/stars/caddyserver/caddy?style=social&color=white)](https://github.com/caddyserver/caddy/stargazers)  
   ⚡ **Modern Web Server with Automatic HTTPS** (Apache-2.0)  
   The pioneer of default zero-touch TLS automation. Caddy provisions, renews, and staples OCSP responses for certificates out-of-the-box. Features **full ACME Renewal Information (ARI) support** including automatic handling of CA-initiated mass revocation events.

2. **[Traefik](https://github.com/traefik/traefik)** [![GitHub_Stars](https://img.shields.io/github/stars/traefik/traefik?style=social&color=white)](https://github.com/traefik/traefik/stargazers)  
   🚀 **Cloud-Native Reverse Proxy & Ingress Controller** (MIT)  
   Seamlessly integrates with Docker, Swarm, Kubernetes, Consul, and AWS to dynamically configure routing and negotiate TLS certificates via ACME (Let's Encrypt, ZeroSSL, custom ACME servers).

3. **[mkcert](https://github.com/FiloSottile/mkcert)** [![GitHub_Stars](https://img.shields.io/github/stars/FiloSottile/mkcert?style=social&color=white)](https://github.com/FiloSottile/mkcert/stargazers)  
   🔒 **Zero-Config Tool for Locally-Trusted Development Certificates** (BSD-3-Clause)  
   Automatically creates and installs a local CA in the system trust store and browser root stores (Firefox, Chrome), issuing valid certificates for `localhost` and local domains with zero configuration.

4. **[acme.sh](https://github.com/acmesh-official/acme.sh)** [![GitHub_Stars](https://img.shields.io/github/stars/acmesh-official/acme.sh?style=social&color=white)](https://github.com/acmesh-official/acme.sh/stargazers)  
   🐚 **Pure Unix Shell ACME Client with Zero External Dependencies** (GPL-3.0)  
   Ultra-lightweight ACME client compatible with Bash, Dash, and Sh. Features out-of-the-box DNS automation supporting **150+ DNS APIs**, ideal for embedded systems, OpenWrt routers, and shared hosting.

5. **[HashiCorp Vault](https://github.com/hashicorp/vault)** [![GitHub_Stars](https://img.shields.io/github/stars/hashicorp/vault?style=social&color=white)](https://github.com/hashicorp/vault/stargazers)  
   🛡️ **Identity-Based Secrets Management & Dynamic PKI Secrets Engine** (BSL-1.1)  
   Functions as an on-demand private Certificate Authority capable of issuing dynamic, short-lived X.509 certificates with built-in ACME server capabilities and CRL/OCSP management.

6. **[Certbot](https://github.com/certbot/certbot)** [![GitHub_Stars](https://img.shields.io/github/stars/certbot/certbot?style=social&color=white)](https://github.com/certbot/certbot/stargazers)  
   📜 **EFF’s Flagship Automated ACME Client** (Apache-2.0)  
   The reference ACME client maintained by the Electronic Frontier Foundation. Standard tool for Linux servers running Nginx and Apache. Version 4.1.0+ includes partial ACME Renewal Information (ARI) support.

7. **[cert-manager](https://github.com/cert-manager/cert-manager)** [![GitHub_Stars](https://img.shields.io/github/stars/cert-manager/cert-manager?style=social&color=white)](https://github.com/cert-manager/cert-manager/stargazers)  
   ☸️ **The De Facto Standard Cloud-Native Certificate Controller for Kubernetes** (Apache-2.0)  
   Manages TLS certificates natively in Kubernetes via Custom Resource Definitions (`Certificate`, `Issuer`, `ClusterIssuer`). Integrates with Let's Encrypt, HashiCorp Vault, Venafi, and external private CAs.

8. **[lego](https://github.com/go-acme/lego)** [![GitHub_Stars](https://img.shields.io/github/stars/go-acme/lego?style=social&color=white)](https://github.com/go-acme/lego/stargazers)  
   🐹 **Pure Go ACME Client Library and CLI** (MIT)  
   The underlying engine powering ACME in Caddy, Traefik, and countless microservices. Features full ARI support (including replacement tracking) and over 100 DNS challenge providers.

9. **[CFSSL](https://github.com/cloudflare/cfssl)** [![GitHub_Stars](https://img.shields.io/github/stars/cloudflare/cfssl?style=social&color=white)](https://github.com/cloudflare/cfssl/stargazers)  
   🌐 **Cloudflare's PKI and TLS Toolkit** (BSD-2-Clause)  
   A battle-tested Go-based suite for signing, verifying, and bundling TLS certificates, serving as an HTTP API-driven PKI daemon and internal CA for high-scale microservices.

10. **[Certimate](https://github.com/certimate-go/certimate)** [![GitHub_Stars](https://img.shields.io/github/stars/certimate-go/certimate?style=social&color=white)](https://github.com/certimate-go/certimate/stargazers)  
    🎨 **Open-Source SSL Automation with Visual Workflow Orchestration** (MIT)  
    Self-hosted CLM providing visual pipelines to apply, renew, and auto-deploy certificates across 70+ domain providers and 160+ target destinations (Cloudflare, AWS, Kubernetes, CDN, WAF) with 20MB RAM footprint.

11. **[step-ca (smallstep certificates)](https://github.com/smallstep/certificates)** [![GitHub_Stars](https://img.shields.io/github/stars/smallstep/certificates?style=social&color=white)](https://github.com/smallstep/certificates/stargazers)  
    🔑 **Automated Private Certificate Authority & Zero-Trust PKI** (Apache-2.0)  
    A versatile private CA supporting ACME, OAuth/OIDC, SCEP, and EST. Built for DevOps, automated microservice mTLS, SSH certificates, and zero-trust perimeter security.

12. **[win-acme](https://github.com/win-acme/win-acme)** [![GitHub_Stars](https://img.shields.io/github/stars/win-acme/win-acme?style=social&color=white)](https://github.com/win-acme/win-acme/stargazers)  
    🪟 **ACME Client for Windows Server & IIS** (Apache-2.0)  
    The premier certificate automation tool for Windows systems with IIS binding management, scheduled tasks, and full ARI support for seamless automated rotation.

13. **[easy-rsa](https://github.com/OpenVPN/easy-rsa)** [![GitHub_Stars](https://img.shields.io/github/stars/OpenVPN/easy-rsa?style=social&color=white)](https://github.com/OpenVPN/easy-rsa/stargazers)  
    🗝️ **CLI-Based CA Management Tool** (GPL-2.0)  
    Maintained by the OpenVPN project, easy-rsa simplifies managing an internal X.509 PKI, creating root/intermediate CAs, key pairs, and certificate revocation lists (CRLs).

14. **[Lemur (Netflix)](https://github.com/Netflix/lemur)** [![GitHub_Stars](https://img.shields.io/github/stars/Netflix/lemur?style=social&color=white)](https://github.com/Netflix/lemur/stargazers)  
    🎬 **Enterprise TLS Certificate Orchestration & Inventory Plane** (Apache-2.0)  
    Netflix's certificate orchestrator acting as a single pane of glass for requesting, tracking, and deploying certificates across AWS IAM, ALB, CloudFront, and internal infrastructure.

15. **[Certify The Web](https://github.com/webprofusion/certify)** [![GitHub_Stars](https://img.shields.io/github/stars/webprofusion/certify?style=social&color=white)](https://github.com/webprofusion/certify/stargazers)  
    🖥️ **GUI Certificate Management Client for Windows** (Open-Source Core)  
    Feature-rich desktop and server UI for managing Let's Encrypt and custom ACME certificates on Windows and IIS servers with built-in deployment scripting.

16. **[Certmate](https://github.com/fabriziosalmi/certmate)** [![GitHub_Stars](https://img.shields.io/github/stars/fabriziosalmi/certmate?style=social&color=white)](https://github.com/fabriziosalmi/certmate/stargazers)  
    📦 **Lightweight Self-Hosted CLM Daemon** (Open-Source)  
    Secure, low-privilege systemd background service providing automated discovery, inventory tracking, renewal, and REST API controls for TLS certificates.

17. **[trust-manager](https://github.com/cert-manager/trust-manager)** [![GitHub_Stars](https://img.shields.io/github/stars/cert-manager/trust-manager?style=social&color=white)](https://github.com/cert-manager/trust-manager/stargazers)  
    🤝 **Operator for Trust Bundle Distribution across Kubernetes** (Apache-2.0)  
    A cert-manager sub-project that distributes and harmonizes public and internal root certificates across all Kubernetes namespaces and pods without secret duplication.

18. **[ILM (Identity Lifecycle Management)](https://github.com/OmniTrustILM/ilm)** [![GitHub_Stars](https://img.shields.io/github/stars/OmniTrustILM/ilm?style=social&color=white)](https://github.com/OmniTrustILM/ilm/stargazers)  
    🏢 **Modular Enterprise Identity, Vault & CBOM Platform** (Apache-2.0)  
    Enterprise PKI platform featuring Cryptographic Bill of Materials (CBOM) scanning, RA and Token profiles, cert-manager external issuers, and connectors for EJBCA and MS ADCS.

19. **[Czertainly](https://github.com/3keycompany/czertainly)** [![GitHub_Stars](https://img.shields.io/github/stars/3keycompany/czertainly?style=social&color=white)](https://github.com/3keycompany/czertainly/stargazers)  
    🏛️ **Comprehensive Enterprise CLM Platform** (MIT)  
    On-premise and containerized CLM supporting hardware security modules (HSM), automated discovery, compliance enforcement, and ACME, EST, and SCEP protocols.

20. **[PKI Manager Web](https://github.com/oriolrius/pki-manager-web)** [![GitHub_Stars](https://img.shields.io/github/stars/oriolrius/pki-manager-web?style=social&color=white)](https://github.com/oriolrius/pki-manager-web/stargazers)  
    🌐 **Self-Hosted Web Interface for Combined X.509 & SSH CAs** (Open-Source)  
    Integrates OpenSSH User and Host CAs with X.509 issuance, Cosmian KMS private key storage, OIDC single sign-on, and Kubernetes external issuer APIs.

21. **[SimpleCA](https://github.com/waucka/simpleca)** [![GitHub_Stars](https://img.shields.io/github/stars/waucka/simpleca?style=social&color=white)](https://github.com/waucka/simpleca/stargazers)  
    📁 **Zero-Friction SQLite-Backed Private CA Manager** (GPL-3.0)  
    Simplifies private X.509 infrastructure without complex OpenSSL configuration files, supporting root/intermediate hierarchies, CRL generation, and PKCS#12 exports.

---

### Enterprise Stacks & Specialized PKI Frameworks

- **[Tiny-PKI](https://pypi.org/project/tiny-pki/)** — Python-based lightweight private CA library and CLI designed for mutual TLS (mTLS) on internal networks, supporting Name Constraints and PKCS#12 bundles.
- **[certmesh](https://pypi.org/project/certmesh/)** — Multi-provider certificate lifecycle automation framework with built-in circuit breakers, Prometheus Pushgateway metrics, and export destinations to Vault KV, AWS Secrets Manager, and local disks.
- **[Secutor](https://www.npmjs.com/package/secutor)** — Self-contained PKI CLI toolkit supporting RSA, ECDSA, and Ed25519 with AES-256-GCM encrypted operational contexts.

---

## 🤝 How to Contribute

We welcome contributions from DevOps engineers, PKI architects, and open-source maintainers!

1. 🍴 **Fork the repository** on GitHub.
2. 🌿 **Create a new branch** (`git checkout -b feature/add-new-clm-tool`).
3. 📝 **Add or update the entry** in `README.md` following the established table or star-ranked format. Keep technical descriptions accurate, factual, and neutral.
4. 🚀 **Submit a Pull Request** with a concise description of your additions.

---

## 💖 Support & Sponsorship

If you find this curated resource helpful for your infrastructure or security workflows:

- ⭐ **Star this repository** to help other platform engineers discover it!
- 🍴 **Fork it** to maintain your own internal PKI checklist.
- 📢 **Share it** on LinkedIn, X/Twitter, Discord, and Reddit.
- ☕ **Support the maintainer**: Buy a coffee or sponsor ongoing maintenance on the **[GitHub Sponsors Dashboard](https://github.com/sponsors/ishandutta2007)**.

Thank you to everyone in the cybersecurity, SRE, and open-source communities for keeping the web secure and automated! ❤️

---

## 📈 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Certificate-Management&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Certificate-Management&type=date&legend=top-left)

---

## ⚠️ Disclaimer & Architectural Insights

- 📌 **Community-Curated**: This repository is a community-driven technical directory provided for informational purposes; entries do not constitute direct endorsements.
- 🔐 **Security & HSM Root of Trust**: Managing private keys requires rigorous access controls. Production enterprise PKI authorities should utilize FIPS 140-2/3 Level 3 Hardware Security Modules (HSMs) and maintain immutable audit logging.
- ⚡ **ARI (ACME Renewal Information - RFC 9636) is Mandatory**: Following modern mass-revocation incidents, ACME clients must support ARI to handle sudden CA-initiated certificate replacements without manual intervention.
- ⏳ **The Short-Lived Certificate Era**: With industry roadmaps reducing TLS certificate validity to 45–47 days, automated lifecycle management is no longer optional—it is a core infrastructure requirement.

---

<p align="center">
  <b>Built with ❤️ for platform engineers, SREs, and security teams worldwide.</b><br>
  <i>Let's make Certificate Lifecycle Management automated, transparent, and resilient.</i>
</p>
