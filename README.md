# Awesome-Contract-Lifecycle-Management-CLM

# Awesome-Contract-Lifecycle-Management-CLM

**Top Contract Lifecycle Management CLM (Opensource) 🌟 Star if you like it! 🌟**



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Contract Authoring, Clause Extraction, Approval Workflows & Self-Hosted Legal Operations*

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Contract Lifecycle Management (CLM)**. These tools enable legal, sales, and operations teams to draft, negotiate, approve, execute, and track contracts—from fully managed enterprise CLM suites with AI-assisted redlining and obligation management to self-hosted platforms that give organizations complete control over sensitive legal documents.



**Examples** include Ironclad, DocuSign CLM, Icertis, Agiloft, PandaDoc, Conga, Contractbook, Concord, LinkSquares, and HubSpot Contract Management (the category leaders in commercial space).



**Open-source emphasis**: This section is expanded with every relevant project for self-hosted CLM, contract AI, and open legal operations infrastructure. **Critical note**: The open-source CLM landscape is emerging rapidly—**draftLegal** positions itself as the open-source alternative to Ironclad + Harvey with agent-first lifecycle management , while **Aakd** takes a narrower, source-linked approach focused on executed contract obligations . Both are early-stage but represent the most complete open-source CLM platforms available. **OpenSign** and **Documenso** handle the e-signature layer but lack renewal tracking . No open-source project matches Icertis's enterprise governance or Ironclad's workflow depth out of the box, but for teams wanting data sovereignty, the options are maturing quickly.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Ironclad](https://ironcladapp.com/)**

  **Enterprise CLM platform** with workflow automation, approval chains, and obligation tracking. Partnered with Harvey for AI-assisted contract intelligence . **Pricing**: Quote-only; enterprise contracts. **Free tier**: None. **Best for**: legal teams needing deep workflow customization and enterprise governance—**trade-off**: six-figure annual cost and data lock-in per open-source alternatives .



- **[DocuSign CLM](https://www.docusign.com/)**

  **Contract lifecycle management** integrated with DocuSign e-signature. **Pricing**: Quote-only; tiered by users and features. **Free tier**: None. **Best for**: organizations already on DocuSign wanting CLM within the same ecosystem.



- **[Icertis](https://www.icertis.com/)**

  **Enterprise contract intelligence** platform with AI-driven obligation extraction and risk scoring. **Pricing**: Quote-only. **Free tier**: None. **Best for**: large enterprises with complex, high-volume contract portfolios needing governance at scale.



- **[Agiloft](https://www.agiloft.com/)**

  **No-code CLM platform** with configurable workflows and strong data model. **Pricing**: Quote-only. **Free tier**: None. **Best for**: organizations wanting CLM customization without development resources.



- **[PandaDoc](https://www.pandadoc.com/)**

  **Document automation** with CPQ, e-signature, and basic CLM capabilities. **Pricing**: Tiered per-user; quote-based for enterprise. **Free tier**: Trial available. **Best for**: sales teams wanting quotes and contracts in one document workflow.



- **[Conga](https://conga.com/)**

  **Revenue lifecycle management** with CLM, CPQ, and document generation. **Pricing**: Quote-only. **Free tier**: None. **Best for**: enterprises wanting CLM integrated with contract management and billing.



- **[Contractbook](https://contractbook.com/)**

  **Contract automation** for SMBs with templates, e-signature, and obligation tracking. **Pricing**: Tiered per-user; quote-based for enterprise. **Free tier**: Trial available. **Best for**: small teams wanting simple contract automation without enterprise complexity.



- **[Concord](https://www.concord.app/)**

  **CLM platform** with collaborative editing, e-signature, and obligation management. **Pricing**: Quote-only. **Free tier**: None. **Best for**: mid-market organizations wanting a modern CLM interface.



- **[LinkSquares](https://linksquares.com/)**

  **AI-powered contract management** with repository search, clause extraction, and reporting. **Pricing**: Quote-only. **Free tier**: None. **Best for**: legal teams wanting AI-driven contract analytics and repository intelligence.



- **[HubSpot Contract Management](https://www.hubspot.com/)**

  **Contract and quote tools** within HubSpot Sales Hub. **Pricing**: Included with Sales Hub tiers; quote-based for enterprise. **Free tier**: Limited basic invoices. **Best for**: HubSpot CRM users wanting contract workflows without leaving the platform—**trade-off**: not a full CLM for complex legal workflows.



## Open-Source GitHub Projects



- **[draftLegal](https://github.com/AniketTati/draft-legal)**

  **Self-hosted, AI-native contract lifecycle management** (license per repo) — **the most ambitious open-source CLM platform**, positioned as the open-source alternative to Ironclad + Harvey . **Features**: **Agent-first architecture**—a chat assistant with ~30 tools over your contracts (search, cite, compare, draft, redline, route approvals); every write proposed on a confirm card first, most undoable; **eight specialist agents** (review, draft, redline, approval summary, playbook review, assist, ask, portfolio) . **Extract + cite**—clauses, dates, and values extracted, risk-scored, and cited to the clause and section; PDF citations open the original at the page . **Portfolio intelligence**—hybrid retrieval (pgvector + Elasticsearch + RRF fusion) for cross-portfolio questions about exposure, counterparties, and renewals . **Full lifecycle**—approval workflows, in-platform e-signature, and post-signature obligation tracking; **redline & negotiate** with conservative/moderate/aggressive options and exact replacement language . **Bring your own model**—Anthropic, OpenAI, or Google Gemini; no vendor lock-in . **Tech stack**: Node.js, Python, React, PostgreSQL, Elasticsearch, pgvector . **Deploy**: Self-hosted (`pnpm dev:setup` then `pnpm dev`) or hosted demo at app.draft-legal.com . **Trade-off**: **Early-stage project**—some agents (ask, portfolio) lack UI; complex setup (Docker, Node 22+, Python 3.11+) . **Best for**: legal and contract operations teams wanting a self-hosted, AI-native CLM that reasons over the entire contract portfolio—with full data sovereignty and no six-figure SaaS costs.



- **[Aakd](https://github.com/aaked-app/aakd)**

  **Open-source, self-hostable CLM for reviewed, source-linked contract operations** (AGPL-3.0) — **the most focused open-source CLM for post-signature obligation management** . **Features**: **Source-linked extraction**—upload executed PDF/DOCX, review extracted fields and obligations with **exact page-level citations**, correct anything wrong, assign owners and due dates . **Obligation and renewal views** with owners, deadlines, reminders, and audit history; **organization-scoped approvals**, comments, notifications, and activity logs . **AI is optional**—extraction, questions, and risk signals are reviewable and **never the canonical source of truth** . **Contract repository** with OCR, folders, tags, search, and version history; REST API and scoped MCP endpoint for agent-assisted, human-controlled workflows; English, French, German, Spanish, and Arabic RTL interfaces . **Tech stack**: TypeScript, PostgreSQL, Redis, MinIO . **Deploy**: Self-hosted (Docker Compose for local; production installer for Ubuntu VM) . **Trade-off**: **Early release (Phase 0)**—customer validation in progress; authoring, template management, and autonomous agents are explicitly out of scope for the first release; new e-signature sends are temporarily paused . **Best for**: contract operations teams wanting to turn executed contracts into reviewed, owned actions with source-linked evidence—without autonomous AI taking over legal judgment.



- **[Wraft](https://github.com/functionary-labs/wraft)**

  **Open-source document lifecycle platform** (AGPL-3.0) — **the most complete open-source option for contract authoring and generation** . **Features**: **Markdown-based templates** with dynamic fields for generating contracts, proposals, and business documents; **review and approval flows** with comments and document history; **electronic signatures** integrated (added in 2025 releases); **audit logs** and **document version comparison**; Google Drive integration; webhooks and pipelines for automation; PDF rendering via Pandoc with LaTeX or Typst . **Contract features** cover vendor records, expiry reminders, audit logs, and document versions . **Tech stack**: Elixir (Phoenix), React, PostgreSQL, MinIO, Typesense . **Deploy**: Self-hosted (Docker Compose; Kubernetes documented) or Wraft Cloud (price not published) . **Trade-off**: **Early project** (~167 GitHub stars as of October 2026); smaller contributor group; rendering chain includes several external services (Pandoc, LaTeX, Java for signing) . **Best for**: teams needing **structured template-based contract generation with approvals and signatures** in one self-hosted workflow—especially those producing repeatable documents like official letters, proposals, and standard contracts.



- **[OpenSign](https://github.com/OpenSignLabs/OpenSign)**

  **Open-source document signing platform** (AGPL-3.0 with carve-out) — **the most recognizable self-hosted e-signature option** for CLM workflows . **Features**: **Templates with signer roles and fields**—set up once, send repeatedly; **familiar signing dashboard** for users coming from commercial tools; compose file for private deployment; tagged releases rather than a moving main branch . **Tech stack**: Per repository. **Deploy**: Self-hosted (compose file at repository root) . **Trade-off**: **No renewal tracking**—e-signature only, not full CLM . **Slowest release cadence** among options checked (no activity between August and late September 2026) . AGPL with carve-out requires license review before shipping derivative work . **Best for**: teams wanting a self-hosted DocuSign alternative with a recognizable signing workflow—paired with a contract repository for full CLM.



- **[LibreSign](https://github.com/LibreSign/libresign)**

  **Nextcloud e-signature app** (AGPL-3.0) — **the cheapest route to self-hosted signing if you already run Nextcloud** . **Features**: E-signature integrated into Nextcloud; storage, identity, and permissions exist already . **Tech stack**: PHP (Nextcloud app). **Deploy**: Nextcloud app. **Trade-off**: **E-signature only**—no CLM workflow, obligation tracking, or clause extraction. **Best for**: Nextcloud users wanting to add contract signing without a separate platform.



- **[Docassemble](https://github.com/jhpyle/docassemble)**

  **Guided interview and document assembly platform** (MIT) — **the most mature open-source tool for guided document drafting**, widely used in legal aid . **Features**: Guided interviews that assemble documents based on user answers; covers drafting, not post-signature lifecycle . **Tech stack**: Python. **Deploy**: Self-hosted. **Trade-off**: **Drafting only**—no CLM workflow, approvals, or obligation tracking. Requires writing interview logic . **Best for**: legal aid organizations and teams needing guided, logic-driven document generation for standard contracts or forms.



- **[Mayan EDMS](https://github.com/mayan-edms/Mayan-EDMS)**

  **Document management system with metadata and workflow states** (Apache-2.0) — **a contract repository foundation** for teams wanting document control without a full CLM . **Features**: Metadata, workflow states, and retention rules; can serve as a contract repository . **Tech stack**: Python/Django. **Deploy**: Self-hosted. **Trade-off**: **Repository only**—renewal dates must be modelled by hand; no clause extraction, approval workflows, or e-signature . **Best for**: teams needing a governed document repository with retention policies—paired with other tools for CLM workflow.



### Additional Strong Open-Source Options



- **ERPNext** — Open-source ERP with native contract fields (LGPL-3.0). **Note**: **The only tool here with renewal dates and obligations natively**, but you accept a full ERP to get them . **Best for**: organizations already running ERPNext wanting contract tracking without a separate CLM.

- **Documenso** — Open-source e-signature platform (AGPL-3.0). **Note**: E-signature only—no renewal tracking or CLM workflow . **Best for**: teams wanting a maintained self-hosted signing option.

- **DocuSeal** — Open-source e-signature platform (AGPL-3.0 with attribution). **Note**: Signing standard PDFs only; no renewal tracking . **Best for**: small teams needing a signing instance running today.

- **Shillinq** — Nextcloud business administration suite with contract lifecycle management (license per repo) . **Note**: Contract management is one module within a broader bookkeeping/procurement suite, not a standalone CLM. **Best for**: Nextcloud users wanting contracts alongside invoicing and procurement.



**Frameworks for building custom systems**: Combine **draftLegal** for AI-native lifecycle management and portfolio intelligence with **Aakd** for source-linked obligation tracking, **Wraft** for template-based authoring and generation, and **OpenSign** or **LibreSign** for e-signature—creating a composable open-source CLM stack. **None of these match Ironclad's enterprise workflow depth or Icertis's governance at scale**, but for teams prioritizing data sovereignty and AI-native workflows, the options are maturing rapidly.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- CLM platforms handling legal contracts and personal data must comply with data protection regulations (GDPR, CCPA, etc.) and implement appropriate access controls for privileged legal documents.

- **The "full CLM" vs. "post-signature CLM" vs. "authoring/generation" vs. "e-signature" distinction is critical.** **Ironclad, DocuSign CLM, Icertis, Agiloft, Conga, and LinkSquares** are **full CLM platforms**—they cover authoring through obligation tracking. **draftLegal** is a **full CLM with AI-native lifecycle**—drafting, review, redline, approval, e-sign, and obligation tracking with agents at every step . **Aakd** is **post-signature CLM**—it focuses on turning executed contracts into reviewed, owned obligations with citations; authoring is explicitly out of scope . **Wraft** is **authoring/generation**—template-based document creation with approvals and signatures, not obligation tracking . **OpenSign, LibreSign, and Documenso** are **e-signature only**—no renewal tracking or CLM workflow . **Choose based on whether you need full lifecycle, post-signature tracking, authoring, or just signing.**

- **draftLegal is the most complete open-source CLM attempt**, combining Ironclad's execution layer with Harvey-style contract intelligence in one self-hosted platform . **The trade-off**: early-stage with complex setup; some agents lack UI. **For teams wanting AI-native CLM with data sovereignty, it is the most ambitious option.**

- **Aakd takes the opposite philosophy**—it is deliberately narrow and human-controlled, with AI as an optional assistant that is **never the canonical source of contract truth** . **The trade-off**: Phase 0 release with authoring out of scope; e-signature sends paused. **For contract operations teams wanting source-linked obligation tracking without autonomous AI risk, it is the more conservative choice.**

- **Wraft fills the authoring gap** that neither draftLegal nor Aakd prioritizes—template-based document generation with dynamic fields, approvals, and signatures . **The trade-off**: early project; rendering chain is complex. **Pair it with Aakd or a repository tool for full lifecycle coverage.**

- **OpenSign is the most recognizable e-signature option** but has no renewal tracking and a slow release cadence . **LibreSign is the cheapest if you already run Nextcloud** . **Neither is a CLM platform**—they are signing layers.

- **Odoo Community does not include the Sign app.** It is often listed as an open-source contract option, but the Sign app requires the paid edition . **Do not evaluate Odoo Community for CLM without verifying the paid tier.**

- **Pricing opacity is universal across commercial CLM vendors.** Ironclad, DocuSign CLM, Icertis, Agiloft, PandaDoc (enterprise), Conga, Contractbook (enterprise), Concord, LinkSquares, and HubSpot (enterprise) all require sales contact for quotes. **Validate with direct vendor conversations against your contract volume and workflow complexity.**

- Self-hosted open-source solutions require proper infrastructure (PostgreSQL, Elasticsearch for draftLegal; MinIO for Aakd/Wraft), security hardening for legal document storage, and ongoing maintenance. **Contracts contain privileged and confidential information**—ensure your deployment meets your organization's security and compliance requirements before migrating production legal documents.



---



**Made for legal operations teams, contract managers, and organizations building transparent CLM solutions.**

Let's make Contract Lifecycle Management more open, data-driven, and contract-sovereign.
