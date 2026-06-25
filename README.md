# Fortinet Unified SASE — Portfolio, Architecture, Licensing & Industry Use-Case Reference

> A single-page, diagram-rich reference covering the **complete Fortinet Unified SASE product portfolio** — what each product does, where it's used, how the services connect, how it's licensed and costed, and how the same platform is assembled differently across industries.

### ▶️ Live page (renders in your browser)
## **https://asad4ntrp2.github.io/fortinet-sase/**

> Click the link above to open the rendered report. (Opening `index.html` *inside the GitHub repo view* shows the raw source code — that's normal; use the GitHub Pages link above to see the live, formatted page.)

---

## 📌 Briefing

**SASE (Secure Access Service Edge)** replaces the legacy "backhaul-to-the-datacenter" model with a globally distributed cloud fabric: users and sites connect to the **nearest Point of Presence (PoP)**, where a full security stack inspects traffic before forwarding it to the Internet, SaaS, or private apps.

**Fortinet Unified SASE** delivers this as a single-vendor convergence of **Secure SD-WAN (networking)** and a cloud-delivered **Security Service Edge / SSE (security)**, built on:

- **One OS** — FortiOS runs on physical FortiGate, virtual FortiGate, and the FortiSASE cloud PoP (the "Hybrid Mesh Firewall"), so policy is identical edge-to-cloud.
- **One agent** — FortiClient delivers VPN, ZTNA posture, SWG, endpoint protection and Digital Experience Monitoring from a single install.
- **One management plane** — FortiManager / the FortiSASE portal, with FortiAnalyzer for logging & SOC analytics.
- **One intelligence source** — FortiGuard Labs feeds real-time threat intel (AV, IPS, web/DNS filtering, inline sandbox, AI/ML) to every enforcement point.

**Three service paths** ride one per-user license:
| Service | Purpose |
|---------|---------|
| **SIA** — Secure Internet Access | Inspected web/internet egress (SWG + FWaaS + IPS + DLP + sandbox) |
| **SPA** — Secure Private Access | Reach private apps via **ZTNA** (per-app) or **SD-WAN hub** (broad/legacy) |
| **Secure SaaS Access** | Inline + API **CASB** to govern sanctioned & shadow SaaS |

**Sovereign SASE:** for data-residency, government, defense and regulated needs, the *same* FortiOS stack can be deployed under your control — **Fortinet-hosted** (standard), **service-provider-hosted** (in-country, locally managed), or **fully self-hosted** (your own DC / private cloud / air-gapped) — so traffic, logs and keys never leave the chosen jurisdiction.

**Commercial model:** licensed **per user, per year**, bundled by edition tier, with **site (thin-edge)** and **private-access bandwidth** as the main capacity add-ons — shifting spend from per-site CapEx to predictable OpEx while consolidating separate SWG/CASB/ZTNA/VPN point-products into one vendor.

---

## 📂 What's in this report (`index.html`)

| # | Section | Contents |
|---|---------|----------|
| 1 | What is Fortinet SASE | The three pillars (single OS / agent / intelligence) |
| 2 | **Product Portfolio** | Full catalog + **Fig 1: 4-layer portfolio map** |
| 3 | Roles & Where Used | Role, placement, and typical users per product |
| 4 | **Reference Architecture** | **Fig 2: on-ramps → PoP stack → destinations** |
| 5 | **Service Connectivity** | **Fig 3: SIA / SPA / Secure SaaS** paths |
| 6 | **Datacenter Connectivity** | **Fig 4: SD-WAN hub vs ZTNA proxy** + comparison |
| 7 | **Sovereign SASE** | Data sovereignty + **Fig 5: deployment spectrum** (Fortinet / SP / self-hosted) |
| 8 | Feature Matrix | Capability → product → SASE pillar |
| 9 | **Licensing Model** | **Fig 6: base subscription + edition tiers + add-ons** |
| 10 | **Costing Model** | Cost components + worked 1,000-user example |
| 11 | Core Use Cases | Six primary deployment patterns |
| 12 | **Industry Blueprints** | **Fig 7: industry map** + 6-industry table + deep-dives |
| 13 | Summary & Glossary | One-paragraph summary + term reference |

**Products covered:** FortiSASE PoP · FWaaS/NGFW · SWG · ZTNA · CASB · DLP · inline Sandbox · IPS · DEM · FortiGate (Secure SD-WAN) · FortiClient + EMS · FortiExtender · FortiAP / FortiSwitch (Thin-Edge) · FortiManager · FortiAnalyzer · FortiGuard Labs.

All diagrams are **inline SVG** (no external dependencies). The page is responsive and prints cleanly to PDF.

---

## 🖥️ Viewing locally

```bash
git clone https://github.com/asad4ntrp2/fortinet-sase.git
cd fortinet-sase
# open index.html in any browser — no build step, no dependencies
```

---

## 📚 References

### Official Fortinet — products & solutions
- **FortiSASE (product)** — https://www.fortinet.com/products/sase
- **FortiSASE documentation** — https://docs.fortinet.com/product/fortisase
- **FortiSASE Administration Guide** — https://docs.fortinet.com/document/fortisase/latest/administration-guide
- **Secure SD-WAN** — https://www.fortinet.com/products/sd-wan
- **ZTNA / Application Access** — https://www.fortinet.com/solutions/enterprise-midsize-business/network-access/application-access
- **Next-Generation Firewall (NGFW)** — https://www.fortinet.com/products/next-generation-firewall
- **FortiGate** — https://www.fortinet.com/products/fortigate
- **FortiOS** — https://www.fortinet.com/products/fortigate/fortios
- **FortiClient** — https://www.fortinet.com/products/forticlient
- **FortiClient / FortiSASE Agent** — https://www.fortinet.com/products/forticlient/fortisase-agent
- **FortiManager** — https://www.fortinet.com/products/management/fortimanager
- **FortiAnalyzer** — https://www.fortinet.com/products/management/fortianalyzer
- **FortiAP (Wireless Access Points)** — https://www.fortinet.com/products/wireless-access-points
- **FortiGuard Labs (threat intelligence)** — https://www.fortinet.com/fortiguard/labs

### Concept / glossary
- **What is SASE?** — https://www.fortinet.com/resources/cyberglossary/sase
- **What is SSE (Security Service Edge)?** — https://www.fortinet.com/resources/cyberglossary/security-service-edge-sse
- **What is CASB?** — https://www.fortinet.com/resources/cyberglossary/casb

> All reference links were verified as reachable at the time of publishing.

---

## ⚠️ Disclaimer

This is an **independent educational / planning reference**, not official Fortinet documentation. **All pricing, edition names, and licensing-tier figures are illustrative planning placeholders only** — Fortinet's list pricing and SKUs change and are heavily volume-discounted. **Always validate licensing and cost with an official Fortinet quote** before relying on any figure. Product names are trademarks of Fortinet, Inc.

---

*Authored by **Asad Yaseen** · [github.com/asad4ntrp2](https://github.com/asad4ntrp2)*
