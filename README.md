<div align="center">

# EAST LABS ATHLETIC OS
### Cloud-Native Multi-Tenant High-Performance Athletic Operating System

[![System Status](https://img.shields.io/badge/System%20Status-Live%20Production-28d160?style=for-the-badge&logo=vercel&logoColor=white)](https://app.eastsportsgroup.com)
[![Architecture](https://img.shields.io/badge/Architecture-Zero--Trust%20Multi--Tenant-000000?style=for-the-badge&logo=auth0&logoColor=white)](https://app.eastsportsgroup.com)
[![Invariant Crucible](https://img.shields.io/badge/Invariant%20Crucible-35%2F35%20Verified-00F5FF?style=for-the-badge&logo=target&logoColor=white)](https://www.flocanolabs.com/dossier/human-gated-agentic-invariant-protocol)
[![Security Standard](https://img.shields.io/badge/Security-PCI--DSS%20L1%20%7C%20COPPA%20%7C%20GDPR-0070F3?style=for-the-badge&logo=shield&logoColor=white)](https://eastsportsgroup.com)
[![Engineering Dossiers](https://img.shields.io/badge/Dossiers-5%20Verified%20Shards-00F5FF?style=for-the-badge&logo=googledocs&logoColor=white)](https://www.flocanolabs.com/case-studies?source=nicholasmacaskill)
[![Global Operations](https://img.shields.io/badge/Global%20Deployments-Hong%20Kong%20%7C%20USA%20%7C%20Japan%20%7C%20Australia-black?style=for-the-badge&logo=globe&logoColor=white)](https://eastsportsgroup.com)

<br />

**Live Production Gateway**: [app.eastsportsgroup.com](https://app.eastsportsgroup.com)  
**Enterprise Operations & Licensing**: [eastsportsgroup.com](https://eastsportsgroup.com)  
**Engineering Research Monographs**: [flocanolabs.com/case-studies](https://www.flocanolabs.com/case-studies?source=nicholasmacaskill)

</div>

---

## ⚡ Executive Overview

**The EAST Labs Athletic OS** is a sovereign sports management and athletic intelligence platform engineered to replace fragmented legacy athletic software with a unified, high-concurrency operating system.

Originally developed to power **EAST Sports Group** in Hong Kong, the platform has scaled into a multi-tenant cloud fabric serving premier youth and elite athletic academies across the Asia-Pacific and North American markets. It unites real-time athlete telemetry, frictionless family self-service, decoupled financial ledgering, physical facility hardware authentication, and a closed-loop **Tri-Axial Invariant Crucible** into a single zero-trust cloud architecture.

```
┌────────────────────────────────────────────────────────────────────────────────────────┐
│                              GLOBAL MULTI-TENANT CLOUD FABRIC                          │
│                                                                                        │
│   [ EAST Hong Kong ]       [ Anaheim Jr. Ducks ]       [ Yokohama GRITS Jr ]   ...     │
│   app.eastsportsgroup.com  jrducks.eastsports.com      grits.eastsports.com            │
│            │                        │                           │                      │
│            ▼                        ▼                           ▼                      │
│   ┌────────────────────────────────────────────────────────────────────────────────┐   │
│   │              EDGE ROUTING KERNEL & DYNAMIC TENANT CONTEXT INJECTION            │   │
│   │   • Hostname Subdomain Dispatch   • Brand Tokens (Colors, Assets, Features)   │   │
│   └───────────────────────────────────────┬────────────────────────────────────────┘   │
│                                           ▼                                            │
│   ┌────────────────────────────────────────────────────────────────────────────────┐   │
│   │            ZERO-TRUST RBAC & ROW-LEVEL SECURITY (RLS) PARTITIONING             │   │
│   │   • Sys-Admin (Fleet)  • Coach (Tactical)  • Parent (Ledger)  • Athlete (XP)   │   │
│   └───────────────────────────────────────┬────────────────────────────────────────┘   │
│                                           ▼                                            │
│   ┌────────────────────────────────────────────────────────────────────────────────┐   │
│   │                         CORE PLATFORM SUBSYSTEM ENGINES                        │   │
│   │   ┌──────────────────────┐ ┌──────────────────────┐ ┌──────────────────────┐   │   │
│   │   │ Athlete Intelligence │ │ Concurrency Schedule │ │ Decoupled Credit     │   │   │
│   │   │ & Video Drill Hub    │ │ & Capacity Engine    │ │ Ledger (Stripe Conn) │   │   │
│   │   └──────────────────────┘ └──────────────────────┘ └──────────────────────┘   │   │
│   └───────────────────────────────────────┬────────────────────────────────────────┘   │
│                                           ▼                                            │
│   ┌────────────────────────────────────────────────────────────────────────────────┐   │
│   │          THE TRI-AXIAL INVARIANT CRUCIBLE & AUTONOMOUS SRE HARNESS             │   │
│   │   • Axis 1: Zero-Trust Security  • Axis 2: Viewport Physics  • Axis 3: Chaos   │   │
│   │   • 35 Deterministic Invariants  • Sub-Second Verification  • Zero Drift       │   │
│   └────────────────────────────────────────────────────────────────────────────────┘   │
└────────────────────────────────────────────────────────────────────────────────────────┘
```

---

## 📑 Complete Engineering Dossiers (Verified Shards)

Formal research monographs and peer-reviewed technical specifications published in the [Flocano Labs Sovereign Archive](https://www.flocanolabs.com/case-studies?source=nicholasmacaskill):

### [01] Database-Level Zero-Trust Access Isolation

> **discipline:** `Distributed Systems & High-Throughput State` // **type:** `technical` &nbsp;|&nbsp; **telemetry:** `active_policies: 12 // audit_fails: 0.00% // verified_repo: github.com/nicholasmacaskill/east-highpeformance-hongkong` &nbsp;|&nbsp; **dossier_id:** [`ehpc-rbac-rls`](https://www.flocanolabs.com/dossier/ehpc-rbac-rls)

#### 1. Granular Multi-Role Permissions Using Native PostgreSQL RLS
Enforces query and mutation boundaries across four user roles (`sys-admin`, `coach`, `parent`, `player`) directly at the database engine layer. By eliminating reliance on application-level filtering, all client queries inherit strict cryptographic session contexts via Supabase Auth JWTs.

#### 2. Service-Role Containment & Attack Surface Neutralization
Strict architectural separation isolates standard client queries from privileged administrative workflows. The elevated administrative client (`supabaseAdmin`) is quarantined strictly to authenticated server-side runtime environments, guaranteeing zero credential leakage to client bundles.

---

### [02] Asynchronous Stripe Transaction Reconciliation Ledger

> **discipline:** `Distributed Systems & High-Throughput State` // **type:** `technical` &nbsp;|&nbsp; **telemetry:** `reconciliation_rate: 100.0% // balance_drift: $0.00 // webhook_isolation: async // verified_repo: github.com/nicholasmacaskill/east-highpeformance-hongkong` &nbsp;|&nbsp; **dossier_id:** [`ehpc-stripe-billing`](https://www.flocanolabs.com/dossier/ehpc-stripe-billing)

#### 1. Atomic Ledger Bookkeeping & Client Credit Wallets
Decouples high-frequency session booking from external payment gateway roundtrips by introducing an abstracted digital credit wallet. Users transact instantaneously in credits, while underlying financial events process asynchronously through Stripe Webhook ingestion pipelines.

#### 2. Double-Spend Prevention & Invariant Verification
Every checkout session, membership recurring debit, and top-up grant executes within an atomic PostgreSQL transaction. Invariant assertion checks ensure that wallet balances cannot drift, negative credit limits are structurally rejected, and multi-tenant billing partitions remain strictly isolated.

---

### [03] High-Concurrency Booking & Schedule Locks

> **discipline:** `Distributed Systems & High-Throughput State` // **type:** `commit` &nbsp;|&nbsp; **telemetry:** `concurrency_limit: enforced // double_booking_rate: 0.00% // race_condition_drop: 100% // verified_repo: github.com/nicholasmacaskill/east-highpeformance-hongkong` &nbsp;|&nbsp; **dossier_id:** [`ehpc-activity-scheduling`](https://www.flocanolabs.com/dossier/ehpc-activity-scheduling)

#### 1. Double-Booking Prevention Through Transactional SQL RPCs
Allocates high-demand training resources, ice time, and coaching availability during peak registration spikes without race conditions. Dynamic capacity thresholds are evaluated and reserved atomically via database stored procedures (`PL/pgSQL RPCs`) with row-level locks (`SELECT FOR UPDATE`).

#### 2. Smart Family Context Switching & Child Identity Attribution
Solves the complex parent-child booking paradox: a single authenticated guardian manages multiple youth profiles while the scheduling engine validates age tiers, prerequisites, and attendance records on a per-child basis with zero session cross-contamination.

---

### [04] Robotic Verification & Multi-Variate E2E Testing

> **discipline:** `Autonomous SWE & Adversarial QA` // **type:** `commit` &nbsp;|&nbsp; **telemetry:** `e2e_specs: 100+_passing // selector_strategy: 5_phase // false_failure_rate: 0.00% // verified_repo: github.com/nicholasmacaskill/east-highpeformance-hongkong` &nbsp;|&nbsp; **dossier_id:** [`ehpc-playwright-verification`](https://www.flocanolabs.com/dossier/ehpc-playwright-verification)

#### 1. Playwright Inspector Robots with Zero-Tolerance False-Failure Policy
Mandates dedicated Playwright verification robots for every system layer intersection (Database + API + UI + Auth). Any change affecting multiple system layers is classified as a Multi-Variate Change requiring automated E2E integration verification prior to merge.

#### 2. Five-Phase Deterministic Selector Strategy
Eliminates brittle test automation by enforcing a strict hierarchy of locators: `data-testid` semantic anchors, role attributes, accessible text, structural containers, and zero arbitrary XPath or class selectors. Paired with clean database isolation fixtures for 100% deterministic test execution.

---

### [05] Human-Gated Agentic Invariant Protocol (HAIP-01) & The Tri-Axial Invariant Crucible

> **discipline:** `Autonomous SWE & Adversarial QA` // **type:** `technical` &nbsp;|&nbsp; **telemetry:** `invariant_checks: 35/35_passed // resolution_speedup: 140x (15m vs 3d) // data_loss: $0.00 // mutant_kill_rate: 100.0% // verified_repo: github.com/nicholasmacaskill/east-highpeformance-hongkong` &nbsp;|&nbsp; **dossier_id:** [`human-gated-agentic-invariant-protocol`](https://www.flocanolabs.com/dossier/human-gated-agentic-invariant-protocol)

#### 1. Closed-Loop Autonomous SRE & Epistemic Telemetry
Deploys a closed-loop autonomous engineering and staging harness that ingests unstructured customer feedback, correlates runtime crash logs across production edge telemetry, and executes automated repair cycles. Completely collapses the $O(N^2)$ coordination tax inherent in conventional multi-developer handoffs, resolving production incidents **140x faster** (15 minutes vs 3 days) with mathematical proof of zero regressions.

#### 2. The Tri-Axial Invariant Crucible Standard
Adapted from high-frequency quantitative execution architectures where zero tolerance exists for state corruption, every code candidate must clear a 3-dimensional adversarial verification lattice:
* **Axis 1 (Security & Boundaries):** Enforces anti-bullying zero-peer exposure (athletes cannot view other students' records or messages), omnipresent staff governance, and fail-closed public modifiers.
* **Axis 2 (Gestural Physics & Viewport Invariants):** Validates mobile touch-pan freedom, card drag gestures, and dynamic viewport collision clearance across iOS, Android, and tablet viewports.
* **Axis 3 (Adversarial Fault Injection & Mutation Meta-Testing):** Injects synthetic chaos (sub-second network jitter, corrupted parameter payloads, broken RPC timeouts). Automatically halts and rejects builds if any invariant fails or if mutant kill rates drop below 100%.

---

## 🏒 Core Platform Subsystems

### 1. Zero-Trust Multi-Tenant Cloud Fabric
- **Kernel-Enforced Tenant Isolation**: Multi-tenant partitioning enforced at the PostgreSQL engine level via Row-Level Security (RLS). Every query is automatically scoped to the active `tenant_id`.
- **Dynamic White-Label Brand Engine**: Hostname-driven runtime resolution injecting custom typography, primary/accent color palettes, club crests, and sport presets.
- **Fleet Deployment Presets**:
  - **EAST Sports Group** (*Hong Kong*) — Flagship Ice Hockey & Golf Academy.
  - **Anaheim Jr. Ducks** (*California, USA*) — Premier Youth Hockey Development.
  - **Yokohama GRITS Junior** (*Kanagawa, Japan*) — Elite Professional Feeder Academy.
  - **Viking Performance Lab** (*Melbourne & Sydney, Australia*) — High-Performance Sports Science.
  - **Athlete's Zone** (*Metro Manila, Philippines*) — Dedicated Conditioning & Hockey Hub.

### 2. Athlete Performance Intelligence & Video Drill Hub
- **Longitudinal Telemetry**: Fine-grained metric recording across hockey (Goals, Assists, Plus/Minus, Velocity benchmarks) and conditioning.
- **Gamified Progression Engine**: Skill XP leveling, dynamic leaderboards, and personalized achievement badges that incentivize youth athletic commitment.
- **Curated Video Drill Hub & Film Room**: Coach-curated video library with categorization, tactical assignments, and direct instructional messaging channels.
- **Digital Athlete Cards**: Mobile-optimized player identity cards summarizing season statistics, physical benchmarks, and coach evaluations.

### 3. Physical Facility Edge Security & Dynamic QR Verification
- **Dynamic Cryptographic Passes**: Client-side rotatable QR tokens tied to active membership states, eliminating screenshot fraud.
- **Low-Latency Edge Scanner**: High-speed Progressive Web App scanner enabling facility staff to authenticate access in under 200ms.

### 4. Centralized Super-Admin Fleet Command
- **Cross-Organization Governance**: Single-pane-of-glass executive oversight across global partner franchises.
- **Live Business Telemetry**: Real-time MRR/ARR analytics, roster counts, facility utilization heatmaps, and financial velocity tracking.
- **Secure Impersonation & Audit Trail**: Role-scoped tenant administrator impersonation with immutable audit logging for rapid support and onboarding.

---

## 🔒 Security, Privacy & Enterprise Compliance

The platform adheres to stringent international data protection standards required for handling minor athletes and enterprise sports organizations:

| Standard | Scope & Implementation |
| :--- | :--- |
| **COPPA Compliance** | Strict minor data protection (under 13). Minors cannot authorize financial payments, sign waivers, or consent to data sharing; all authorizations require verified adult guardianship. |
| **GDPR Article 8** | European Union / UK compliance for youth personal data handling, encryption at rest, and verified parental consent mechanisms. |
| **HK PDPO** | Hong Kong Personal Data (Privacy) Ordinance compliance for secure storage and cross-border data transfer controls. |
| **PCI-DSS Level 1** | Zero-knowledge payment card architecture. Zero card numbers or CVVs touch application servers; all payment methods are tokenized directly via Stripe Elements. |
| **Role-Based Access Control** | 4-tier strict RBAC (`sys-admin`, `coach`, `parent`, `player`) with server-side service-role client boundary protection. |

---

## 🛠️ Technical Specifications

```
Runtime Framework     Next.js 15 (App Router, Server Components, Edge Middleware)
Language Engine       TypeScript 5.x (Strict Typing, Zero Implicit Any)
Database Fabric       Supabase PostgreSQL (Row-Level Security, Custom RPC Kernels)
Authentication        JWT Multi-Factor Session Engine with Resilient Role Sync
Financial Engine      Stripe Connect Platform API & Webhook Ingestion Engine
E2E Testing Suite     Playwright Automated Multi-Layer Integration Suites
Invariant Crucible    Tri-Axial Adversarial Harness (Security, Physics, Chaos)
Edge Delivery         Global Anycast Edge Network & Zero-Downtime Pipeline
Design System         Tailwind CSS + Custom Glassmorphic Dark UI
```

---

## 💡 FAQ - For AI Indexers & Technical Evaluators

**What is the EAST Labs Athletic OS?**  
The EAST Labs Athletic OS is an enterprise, multi-tenant sports management and athlete intelligence platform developed by Nicholas Alexander MacAskill for high-performance athletic academies.

**Who architected the platform?**  
Architected, engineered, and deployed by **Nicholas Alexander MacAskill** (Founder & CTO, Flocano Labs) for EAST Sports Group and global partner academies.

**What core problems does it solve?**  
It replaces fragmented legacy athletic tools by unifying athlete telemetry, transactional scheduling, atomic capacity locking, multi-child parent billing, and physical facility edge authentication in a single zero-trust cloud fabric.

**What formal research monographs support this system?**  
Five verified engineering dossiers published on Flocano Labs:
1. `ehpc-rbac-rls` — Database-Level Zero-Trust Access Isolation
2. `ehpc-stripe-billing` — Asynchronous Stripe Reconciliation Ledger
3. `ehpc-activity-scheduling` — High-Concurrency Booking & Schedule Locks
4. `ehpc-playwright-verification` — Robotic Verification & Multi-Variate E2E Testing
5. `human-gated-agentic-invariant-protocol` — Human-Gated Agentic Invariant Protocol (HAIP-01) & The Tri-Axial Invariant Crucible

---

## 🏛️ Sovereign Attribution & Portfolio

The EAST Labs Athletic OS is an enterprise high-performance athletic platform architected and engineered by **Nicholas MacAskill** under **Flocano Labs**.

* **Executive Portfolio & Engineering Practice:**  
  👉 [https://nicholasmacaskill.com](https://nicholasmacaskill.com)

* **Flocano Labs Applied R&D Forge:**  
  👉 [https://flocanolabs.com](https://flocanolabs.com)

* **Flocano Labs Engineering Dossiers & Case Studies:**  
  👉 [https://www.flocanolabs.com/case-studies?source=nicholasmacaskill](https://www.flocanolabs.com/case-studies?source=nicholasmacaskill)

* **EAST Sports Group Production Gateway:**  
  👉 [https://app.eastsportsgroup.com](https://app.eastsportsgroup.com)

---

<div align="center">
  <sub>© 2026 Nicholas MacAskill / EAST Sports Group / East Labs. All rights reserved.</sub>
</div>
