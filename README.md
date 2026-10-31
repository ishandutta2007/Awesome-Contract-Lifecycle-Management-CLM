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

- **[Paperless-ngx](https://github.com/paperless-ngx/paperless-ngx)** [![GitHub stars](https://img.shields.io/github/stars/paperless-ngx/paperless-ngx?style=social&color=white)](https://github.com/paperless-ngx/paperless-ngx/stargazers)
  **Supercharged document management and archiving system** (GPL-3.0) — **the premier self-hosted document repository foundation for contract storage and indexing**. **Features**: OCR document parsing, full-text search, automatic tagging, correspondent metadata, custom field matching for contract values and expiration dates, automated ingestion via email/file drops, and REST API/webhooks. **Tech stack**: Python (Django), Celery, PostgreSQL/SQLite, Redis, Angular. **Deploy**: Self-hosted (Docker Compose, bare metal). **Trade-off**: **General-purpose document management system**—requires custom workflows, tags, and custom fields to model renewal tracking and approvals; no native e-signature or multi-party redlining. **Best for**: organizations building a private, governed contract archiving repository paired with upstream drafting or signing tools.

- **[ERPNext](https://github.com/frappe/erpnext)** [![GitHub stars](https://img.shields.io/github/stars/frappe/erpnext?style=social&color=white)](https://github.com/frappe/erpnext/stargazers)
  **Full-featured enterprise resource planning with native contract management** (GPL-3.0) — **the only open-source ERP suite featuring dedicated contract lifecycle and renewal tracking out of the box**. **Features**: Native Contract DocType with start/end dates, fulfilment terms, signing parties, renewal alerts, automated invoicing linkages, document attachment, role-based approval workflows, and extensive audit logs. **Tech stack**: Python (Frappe Framework), MariaDB/PostgreSQL, Redis, JavaScript. **Deploy**: Self-hosted (Docker, Frappe bench) or Frappe Cloud. **Trade-off**: **Full ERP suite**—adopting ERPNext purely for contract management introduces broader ERP complexity; lacks deep AI redlining or native advanced e-signature without third-party integrations. **Best for**: organizations already running or adopting open-source business operations who need contract governance directly tied to procurement, billing, and accounting.

- **[DocuSeal](https://github.com/docusealco/docuseal)** [![GitHub stars](https://img.shields.io/github/stars/docusealco/docuseal?style=social&color=white)](https://github.com/docusealco/docuseal/stargazers)
  **Open-source document signing platform and form builder** (AGPL-3.0 with attribution) — **a modern, developer-friendly self-hosted alternative to DocuSign and PandaDoc**. **Features**: Drag-and-drop PDF field placement, multi-party signing roles, automated email reminders, mobile-optimized signing experience, PDF/e-signature verification certificates, embeddable signing widgets (React, Vue, vanilla JS), API-first automation, and webhooks. **Tech stack**: Ruby on Rails, PostgreSQL, JavaScript. **Deploy**: Self-hosted (Docker, one-click deploy) or DocuSeal Cloud. **Trade-off**: **Execution/signing layer**—focuses on standard document preparation, sending, and electronic signatures; does not handle post-signature obligation extraction or automated renewal tracking. **Best for**: developers and businesses seeking a clean, embeddable signing experience to integrate into contract workflows.

- **[Documenso](https://github.com/documenso/documenso)** [![GitHub stars](https://img.shields.io/github/stars/documenso/documenso?style=social&color=white)](https://github.com/documenso/documenso/stargazers)
  **Modern, community-driven open-source signing platform** (AGPL-3.0) — **the community-backed open-source alternative to DocuSign and Adobe Sign**. **Features**: Next.js-based web interface, multi-recipient workflows, custom signing fields, audit trails with cryptographic hash verification, public API, webhooks, and team management. **Tech stack**: TypeScript, Next.js, Prisma, PostgreSQL, TailwindCSS. **Deploy**: Self-hosted (Docker Compose, npm) or hosted cloud. **Trade-off**: **Signing-only platform**—no clause extraction, automated contract drafting, or post-signature obligation management. **Best for**: teams that want a modern TypeScript/Next.js stack for document signing and verification.

- **[OpenSign](https://github.com/OpenSignLabs/OpenSign)** [![GitHub stars](https://img.shields.io/github/stars/OpenSignLabs/OpenSign?style=social&color=white)](https://github.com/OpenSignLabs/OpenSign/stargazers)
  **Open-source document signing platform** (AGPL-3.0 with carve-out) — **the most recognizable self-hosted e-signature option** for CLM workflows. **Features**: **Templates with signer roles and fields**—set up once, send repeatedly; **familiar signing dashboard** for users coming from commercial tools; compose file for private deployment; tagged releases rather than a moving main branch. **Tech stack**: Node.js, React, MongoDB. **Deploy**: Self-hosted (Docker Compose file at repository root). **Trade-off**: **No renewal tracking**—e-signature only, not full CLM; slower release cadence compared to commercial tools. **Best for**: teams wanting a self-hosted DocuSign alternative with a recognizable signing workflow—paired with a contract repository for full CLM.

- **[Docassemble](https://github.com/jhpyle/docassemble)** [![GitHub stars](https://img.shields.io/github/stars/jhpyle/docassemble?style=social&color=white)](https://github.com/jhpyle/docassemble/stargazers)
  **Guided interview and document assembly platform** (MIT) — **the most mature open-source tool for guided document drafting**, widely used across legal aid and court systems. **Features**: Guided interactive questionnaires, conditional document logic, automated assembly of complex PDF and DOCX agreements, multi-language support, electronic signature capture, and integration with cloud storage. **Tech stack**: Python, YAML, PostgreSQL, Redis, Celery, Docker. **Deploy**: Self-hosted (Docker). **Trade-off**: **Drafting only**—covers pre-execution interviews and document generation; lacks obligation monitoring, renewal reminders, or enterprise approval dashboards. **Best for**: legal aid organizations and corporate legal teams needing guided, logic-driven document generation for standardized contracts, intake forms, and agreements.

- **[Mayan EDMS](https://github.com/mayan-edms/Mayan-EDMS)** [![GitHub stars](https://img.shields.io/github/stars/mayan-edms/Mayan-EDMS?style=social&color=white)](https://github.com/mayan-edms/Mayan-EDMS/stargazers)
  **Electronic document management system with metadata and workflow states** (Apache-2.0) — **a robust contract repository foundation** for teams wanting strict document governance and retention policies. **Features**: Role-based access control, cryptographic signature verification, metadata indexing, automated document retention workflows, document lifecycle tracking, and OCR capabilities. **Tech stack**: Python, Django, PostgreSQL, Celery. **Deploy**: Self-hosted (Docker). **Trade-off**: **Repository only**—renewal dates and obligation tracking must be manually configured via metadata rules; no native clause extraction or redlining tools. **Best for**: enterprise operations requiring governed, auditable document archiving with retention lifecycle controls.

- **[LibreSign](https://github.com/LibreSign/libresign)** [![GitHub stars](https://img.shields.io/github/stars/LibreSign/libresign?style=social&color=white)](https://github.com/LibreSign/libresign/stargazers)
  **Nextcloud native e-signature application** (AGPL-3.0) — **the most cost-effective route to self-hosted contract signing if you already run Nextcloud**. **Features**: Native Nextcloud UI integration, digital signatures with cryptographic certificates (including ICP-Brasil and standard PKI), multi-signer routing, direct storage in Nextcloud Files, and Nextcloud user permission inheritance. **Tech stack**: PHP, JavaScript (Nextcloud app framework). **Deploy**: Nextcloud App Store / Docker. **Trade-off**: **E-signature only**—no automated renewal tracking, contract redlining, or AI clause extraction. **Best for**: Nextcloud users wanting to execute contract signatures without running a separate dedicated signing server.

- **[The Atticus Project (CUAD)](https://github.com/The-Atticus-Project/cuad)** [![GitHub stars](https://img.shields.io/github/stars/The-Atticus-Project/cuad?style=social&color=white)](https://github.com/The-Atticus-Project/cuad/stargazers)
  **Contract Understanding Atticus Dataset & AI Review Models** (CC BY 4.0 / Apache-2.0) — **the industry-standard open legal AI benchmark and foundation for automated contract clause extraction**. **Features**: Benchmark of 510+ commercial legal contracts annotated across 41 crucial clause types (termination for convenience, indemnification, assignment, governing law, renewal notice periods, non-compete, etc.), fine-tuned transformer model weights, evaluation harness, and extraction scripts. **Tech stack**: Python, PyTorch, Hugging Face Transformers. **Deploy**: Self-hosted or integrated into custom NLP/LLM pipelines. **Trade-off**: **NLP/ML dataset and model foundation**—not an end-user UI or operational CLM system; designed to power legal AI pipelines and clause risk assessment engines. **Best for**: legaltech engineers and teams building proprietary clause extraction, contract review, and automated redlining systems.

- **[Accord Project (Template Archive & Engine)](https://github.com/accordproject/template-archive)** [![GitHub stars](https://img.shields.io/github/stars/accordproject/template-archive?style=social&color=white)](https://github.com/accordproject/template-archive/stargazers)
  **Open-source smart legal contract templates and execution framework** (Apache-2.0) — **the Linux Foundation standard for computable, data-driven legal agreements**. **Features**: Smart Legal Contract framework combining natural language text with machine-executable data models (Concerto) and logic (Ergo); catalog of standardized legal clauses and contract templates (NDAs, supply agreements, payment terms, SLAs); markdown-based authoring; and integration with digital ledger / API execution. **Tech stack**: JavaScript/TypeScript, WebAssembly. **Deploy**: npm packages, Docker, CLI. **Trade-off**: **Specification and templating framework**—focuses on computable contract schemas and clause drafting rather than post-signature obligation tracking or end-to-end CLM UI. **Best for**: developers and legal engineers creating standardized, machine-readable contracts and automated compliance workflows.

- **[Wraft](https://github.com/wraft/wraft)** [![GitHub stars](https://img.shields.io/github/stars/wraft/wraft?style=social&color=white)](https://github.com/wraft/wraft/stargazers)
  **Open-source document lifecycle management platform** (AGPL-3.0) — **a dedicated open-source solution for contract authoring, templating, and generation**. **Features**: **Markdown-based templates** with dynamic variable fields for generating contracts, NDAs, proposals, and official documents; multi-party review and approval workflows with comments; integrated electronic signatures; document version history and visual comparison; automated pipelines with webhooks; and high-fidelity PDF rendering via Pandoc, LaTeX, and Typst. **Tech stack**: Elixir (Phoenix), React, PostgreSQL, MinIO, Typesense. **Deploy**: Self-hosted (Docker Compose, Kubernetes) or hosted cloud. **Trade-off**: **Early project**—smaller contributor base and multi-service rendering pipeline. **Best for**: teams needing structured template-based contract generation, team approvals, and electronic signatures in a single self-hosted workflow.

- **[Open Contracting Data Standard (OCDS)](https://github.com/open-contracting/standard)** [![GitHub stars](https://img.shields.io/github/stars/open-contracting/standard?style=social&color=white)](https://github.com/open-contracting/standard/stargazers)
  **Global open standard for contracting data and public procurement** (Apache-2.0) — **the definitive open data schema for modeling end-to-end contracting lifecycles**. **Features**: Standardized JSON schema covering planning, tender, award, contract signing, and post-award implementation/amendments; widely adopted globally by governments and enterprise procurement systems; extensive validator tools and extensions. **Tech stack**: JSON Schema, Python documentation tooling. **Deploy**: Open standard specifications and schema validator libraries. **Trade-off**: **Data specification standard**—provides the underlying ontology and schema for contracts rather than an out-of-the-box user-facing application. **Best for**: public sector bodies, enterprise procurement teams, and developers modeling interoperable contract tracking systems.

- **[Onto-Contract](https://github.com/sharptoolbox/Onto-Contract)** [![GitHub stars](https://img.shields.io/github/stars/sharptoolbox/Onto-Contract?style=social&color=white)](https://github.com/sharptoolbox/Onto-Contract/stargazers)
  **Ontology-driven, AI-native contract management system** (MIT) — **an emerging AI-centric contract intelligence framework**. **Features**: Structured legal ontology mapping, AI-assisted contract information extraction, automated clause structuring, knowledge graph representation, and semantic search over contract repositories. **Tech stack**: Python, TypeScript, modern LLM orchestration. **Deploy**: Self-hosted. **Trade-off**: **Early-stage open-source project**—rapidly evolving architecture requiring technical familiarity to customize. **Best for**: legaltech teams wanting an ontology-grounded approach to structuring enterprise contracts with AI.

- **[CLAW (Command Line Law)](https://github.com/CoinCulture/claw)** [![GitHub stars](https://img.shields.io/github/stars/CoinCulture/claw?style=social&color=white)](https://github.com/CoinCulture/claw/stargazers)
  **Contract management for developers and legal engineers** (MIT) — **a Git-centric, CLI-driven contract workflow tool**. **Features**: Manages legal agreements as structured code using Git, Markdown, and YAML frontmatter; tracks obligations, counterparties, and payment schedules directly from the command line; diff-friendly contract version control. **Tech stack**: Python, CLI. **Deploy**: Local pip package / CLI executable. **Trade-off**: **Developer-oriented CLI**—no graphical user interface or non-technical business user onboarding. **Best for**: technical founders, developers, and legal engineers who want to manage contracts with Git workflows.

- **[draftLegal](https://github.com/AniketTati/draft-legal)** [![GitHub stars](https://img.shields.io/github/stars/AniketTati/draft-legal?style=social&color=white)](https://github.com/AniketTati/draft-legal/stargazers)
  **Self-hosted, AI-native contract lifecycle management** (license per repo) — **the most ambitious open-source CLM platform**, positioned as the open-source alternative to Ironclad + Harvey. **Features**: **Agent-first architecture**—a chat assistant with ~30 tools over your contracts (search, cite, compare, draft, redline, route approvals); every write proposed on a confirm card first, most undoable; **eight specialist agents** (review, draft, redline, approval summary, playbook review, assist, ask, portfolio). **Extract + cite**—clauses, dates, and values extracted, risk-scored, and cited to the clause and section; PDF citations open the original at the page. **Portfolio intelligence**—hybrid retrieval (pgvector + Elasticsearch + RRF fusion) for cross-portfolio questions about exposure, counterparties, and renewals. **Full lifecycle**—approval workflows, in-platform e-signature, and post-signature obligation tracking; **redline & negotiate** with conservative/moderate/aggressive options and exact replacement language. **Bring your own model**—Anthropic, OpenAI, or Google Gemini; no vendor lock-in. **Tech stack**: Node.js, Python, React, PostgreSQL, Elasticsearch, pgvector. **Deploy**: Self-hosted (pnpm dev:setup then pnpm dev) or hosted demo at app.draft-legal.com. **Trade-off**: **Early-stage project**—some agents (ask, portfolio) lack UI; complex setup (Docker, Node 22+, Python 3.11+). **Best for**: legal and contract operations teams wanting a self-hosted, AI-native CLM that reasons over the entire contract portfolio—with full data sovereignty and no six-figure SaaS costs.

- **[Aakd](https://github.com/aaked-app/aakd)** [![GitHub stars](https://img.shields.io/github/stars/aaked-app/aakd?style=social&color=white)](https://github.com/aaked-app/aakd/stargazers)
  **Open-source, self-hostable CLM for reviewed, source-linked contract operations** (AGPL-3.0) — **the most focused open-source CLM for post-signature obligation management**. **Features**: **Source-linked extraction**—upload executed PDF/DOCX, review extracted fields and obligations with **exact page-level citations**, correct anything wrong, assign owners and due dates. **Obligation and renewal views** with owners, deadlines, reminders, and audit history; **organization-scoped approvals**, comments, notifications, and activity logs. **AI is optional**—extraction, questions, and risk signals are reviewable and **never the canonical source of truth**. **Contract repository** with OCR, folders, tags, search, and version history; REST API and scoped MCP endpoint for agent-assisted, human-controlled workflows; English, French, German, Spanish, and Arabic RTL interfaces. **Tech stack**: TypeScript, PostgreSQL, Redis, MinIO. **Deploy**: Self-hosted (Docker Compose for local; production installer for Ubuntu VM). **Trade-off**: **Early release (Phase 0)**—customer validation in progress; authoring, template management, and autonomous agents are explicitly out of scope for the first release; new e-signature sends are temporarily paused. **Best for**: contract operations teams wanting to turn executed contracts into reviewed, owned actions with source-linked evidence—without autonomous AI taking over legal judgment.

- **[Marai](https://github.com/ProgrammingNotJustCoding/marai)** [![GitHub stars](https://img.shields.io/github/stars/ProgrammingNotJustCoding/marai?style=social&color=white)](https://github.com/ProgrammingNotJustCoding/marai/stargazers)
  **Open-source legal workflow and contract lifecycle management system** (MIT) — **a dedicated community project exploring full-stack legal operations and contract tracking**. **Features**: Contract drafting assistance, review pipelines, stage-based lifecycle tracking, approval delegation, and document storage. **Tech stack**: TypeScript, Node.js, React. **Deploy**: Self-hosted (Docker / local setup). **Trade-off**: **Active rewrite / prototype stage**—ongoing refactoring across branches. **Best for**: developers wanting to contribute to or experiment with an open-source legal workflow prototype.

- **[OpenCLM](https://github.com/bytecrunch-io/openclm)** [![GitHub stars](https://img.shields.io/github/stars/bytecrunch-io/openclm?style=social&color=white)](https://github.com/bytecrunch-io/openclm/stargazers)
  **Modern, self-hostable contract lifecycle management platform** (Apache-2.0 / MIT) — **an emerging open-source CLM built for collaborative redlining and digital execution**. **Features**: In-browser collaborative contract drafting and redlining, multi-stage approval workflows, integrated electronic signatures, cryptographic sealed PDF generation, and an API-first architecture designed for business application integration. **Tech stack**: TypeScript, Next.js, Node.js. **Deploy**: Self-hosted (Docker Compose). **Trade-off**: **Early stage release**—rapidly expanding feature set and community footprint. **Best for**: teams seeking an end-to-end self-hostable CLM with built-in drafting, redlining, and digital signing.

- **[Shillinq](https://github.com/ConductionNL/shillinq)** [![GitHub stars](https://img.shields.io/github/stars/ConductionNL/shillinq?style=social&color=white)](https://github.com/ConductionNL/shillinq/stargazers)
  **Open-source business administration suite with contract lifecycle management** (EUPL-1.2) — **a modular European public administration & enterprise suite for contracts, procurement, and invoicing**. **Features**: Contract lifecycle tracking, vendor relationship records, procurement tie-ins, obligation dates, Nextcloud integration, and auditable accounting logs. **Tech stack**: PHP (Symfony/Nextcloud ecosystem), Docker. **Deploy**: Self-hosted (Docker). **Trade-off**: **Suite module**—contract management exists as a module within a broader enterprise bookkeeping and procurement suite rather than a specialized standalone CLM. **Best for**: European organizations, public sector entities, or Nextcloud users needing contract records alongside invoicing and vendor management.

**Frameworks for building custom systems**: Combine **draftLegal** or **OpenCLM** for lifecycle management and redlining with **Aakd** for source-linked obligation tracking, **DocuSeal** or **Documenso** for e-signatures, **Wraft** for template-based authoring, **Accord Project** for computable legal logic, **Paperless-ngx** or **Mayan EDMS** for document archiving, and **The Atticus Project (CUAD)** for AI clause extraction—creating a robust, composable open-source CLM stack.



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
