# Awesome-Document-Generation

## Top Document Generation Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Template-Driven Document Assembly, Data Merging & Automated Output*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Document Generation**. These tools enable organizations to automatically produce personalized documents—contracts, proposals, invoices, reports, and letters—by merging structured data into templates, eliminating manual drafting while ensuring brand consistency and compliance.



**Examples** include Workday Document Generation, PandaDoc, DocuSign Gen, Conga Composer, Adobe Acrobat Sign, Nintex DocGen, Formstack Documents, SmartIQ, HotDocs, and airSlate (the category leaders).



**Open-source emphasis**: Document Generation is a domain where open-source tooling is **mature at the library level but fragmented as a complete platform**. The strongest active projects are **docxtpl** (Jinja2 templating for DOCX), **Aldina** (theme-driven print-grade PDF generation with a deterministic gate), and **gpdf** (Go-based PDF generation with digital signatures and PDF/A). For survey-driven document assembly, **unlawful-assembly** provides a client-side no-code workflow. Organizations seeking a complete SaaS-equivalent platform must assemble components or adopt a commercial product.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## Sector Overview & Market Dynamics

The global document generation and automation market is estimated at approximately **$3.5 billion to $4.4 billion** (scaling toward upwards of $10 billion to $17 billion when broadly accounting for end-to-end document workflow and Document AI pipelines at a 10–15% CAGR). The sector exhibits a **hybrid market structure: concentrated at the enterprise top tier**—where dominant platform incumbents (Adobe, Workday, DocuSign, Conga) command major enterprise-wide deployments and deeply integrated CRM/ERP workflows—**yet highly fragmented across middle and lower tiers**, where a multitude of specialized ISVs, vertical-specific point solutions, and open-source engines compete to deliver tailored template assembly and developer APIs.



## SaaS/Hosted Platforms

| Platform | Revenue / Valuation | Starting Pricing | Free Tier / Trial Limits | Description |
| :--- | :--- | :--- | :--- | :--- |
| **[Adobe Acrobat Sign](https://www.adobe.com/sign.html)** | ~$23.8B revenue / ~$105B market cap | $12.99/user/month (Acrobat Standard, annual commitment) | 30-day free trial for Acrobat Sign Enterprise (no credit card required) or 7-day free trial for Acrobat Pro | E-signature and enterprise document generation suite integrated into Adobe's document workflow ecosystem. |
| **[Workday Document Generation](https://www.workday.com/)** | ~$8.5B revenue / ~$52B market cap | ~$34 to $100+/employee/year (Core HCM modular bundle) | No self-serve free trial; guided sandbox/evaluation tenant provided via custom enterprise demo | Native document generation within Workday suite producing automated offer letters, statements, and contracts from HR/financial records. |
| **[DocuSign Gen](https://www.docusign.com/)** | ~$3.0B revenue / ~$16.5B market cap | $20/user/month (DocuSign Gen add-on for Salesforce; requires paid eSignature base plan) | 30-day free trial for Salesforce AppExchange integration with full product features | Template-based contract and agreement creation directly merged from Salesforce CRM records. |
| **[Nintex DocGen](https://www.nintex.com/)** | ~$230M revenue / $2.0B valuation (TPG acquisition) | ~$5,000/year (enterprise contract bundle) | 30-day free trial with no credit card required | Automated document generation for Salesforce and SharePoint, creating Word, PDF, Excel, and PowerPoint documents from templates. |
| **[SmartIQ](https://www.smartiq.com/)** | ~$110M+ revenue / $1.8B valuation (Cinven buyout) | Enterprise quote (custom contract via AWS Marketplace / direct) | No self-serve free trial; custom proof-of-concept (PoC) and guided evaluation environments available on request | Intelligent, interview-driven document generation and digital forms platform for complex, regulated enterprise workflows. |
| **[airSlate](https://www.airslate.com/)** | ~$200M revenue / $1.25B valuation (Series C) | $399/month (Growth Plan, 10,000 automation credits, unlimited users) | Permanent Free plan limited to 10 credits/month (or 7-day free trial for signNow plans) | No-code document workflow automation platform combining robotic process automation, template generation, and e-signatures. |
| **[Conga Composer](https://conga.com/)** | ~$250M revenue / $1.25B valuation (Thoma Bravo) | ~$35/user/month (custom quote / baseline tier) | 30-day free trial with 10 user licenses included upon production/sandbox installation | High-volume document generation and reporting suite for Salesforce and Microsoft Dynamics merging data into Word, Excel, and PDF. |
| **[PandaDoc](https://www.pandadoc.com/)** | ~$100M ARR / $1.0B valuation (Series C) | $19/user/month (Starter plan, billed annually) | Permanent Free plan limited to 5 document uploads/sends per month, or 14-day free trial of paid plans | Document automation platform combining drag-and-drop template assembly, proposal generation, and native e-signatures. |
| **[Formstack Documents](https://www.formstack.com/)** | ~$50M ARR / $425M growth round (Silversmith/PSG) | $110/month (Starter tier, 150 document merges/month, 2 users, 10 templates) | 14-day free trial with full template building and integration access (no credit card required) | Document automation engine (formerly WebMerge) merging form submissions and external data sources into PDFs and Word documents. |
| **[HotDocs](https://www.hotdocs.com/)** | ~$220M revenue (Mitratech group) / Multi-billion PE | ~$25/user/month (base tier estimate via enterprise quote) | No self-serve free trial; 30-day temporary evaluation license provisioned through sales / demo | Enterprise template authoring and interview-driven document assembly for legal, banking, and insurance organizations. |



## Open-Source GitHub Projects



- **[typst](https://github.com/typst/typst)** [![GitHub stars](https://img.shields.io/github/stars/typst/typst?style=social&color=white)](https://github.com/typst/typst/stargazers)  

  A modern, markup-based typesetting and document compilation system designed to be powerful and easy to learn (Rust, Apache-2.0); combines the layout expressiveness of LaTeX with programmatic styling, native mathematical typesetting, and instant preview compilation. **Leading modern open-source engine for programmatic document authoring, reports, and publication-ready PDFs.**



- **[react-pdf](https://github.com/diegomura/react-pdf)** [![GitHub stars](https://img.shields.io/github/stars/diegomura/react-pdf?style=social&color=white)](https://github.com/diegomura/react-pdf/stargazers)  

  Modular React-based rendering engine for creating PDF documents directly from declarative JSX components (MIT); runs seamlessly in both Node.js server environments and client-side web browsers with flexbox styling support. **Ideal for web engineering teams generating invoices, dynamic reports, and certificates using React idioms.**



- **[Gotenberg](https://github.com/gotenberg/gotenberg)** [![GitHub stars](https://img.shields.io/github/stars/gotenberg/gotenberg?style=social&color=white)](https://github.com/gotenberg/gotenberg/stargazers)  

  A Docker-powered stateless REST API for converting numerous document formats (HTML, Markdown, DOCX, XLSX, PPTX, images) into standard and PDF/A files (MIT); orchestrates headless Chromium, LibreOffice, and PDF engines within a scalable containerized architecture. **The standard microservice foundation for production-grade document conversion and PDF pipelines.**



- **[pdfmake](https://github.com/bpampuch/pdfmake)** [![GitHub stars](https://img.shields.io/github/stars/bpampuch/pdfmake?style=social&color=white)](https://github.com/bpampuch/pdfmake/stargazers)  

  Client-side and server-side JavaScript document generation engine using pure declarative JSON document definitions (MIT); supports complex tables, margins, vector graphics, image embedding, custom fonts, and pagination without external binary dependencies. **Battle-tested for client-side invoice and statement generation directly in the browser.**



- **[WeasyPrint](https://github.com/Kozea/WeasyPrint)** [![GitHub stars](https://img.shields.io/github/stars/Kozea/WeasyPrint?style=social&color=white)](https://github.com/Kozea/WeasyPrint/stargazers)  

  Visual rendering engine translating HTML and CSS into print-quality PDF documents (BSD-3-Clause); adheres strictly to W3C standards including CSS Paged Media (@page), margins, headers/footers, and page counters. **The definitive Python choice for converting modern CSS/HTML templates into high-fidelity printable business reports.**



- **[docxtemplater](https://github.com/open-xml-templating/docxtemplater)** [![GitHub stars](https://img.shields.io/github/stars/open-xml-templating/docxtemplater?style=social&color=white)](https://github.com/open-xml-templating/docxtemplater/stargazers)  

  Template-based document generator for DOCX, PPTX, and XLSX files from Node.js or browser environments (MIT); allows non-developers to edit templates visually in Word or PowerPoint with tag syntax ({first_name}, {#items}...{/items}), merging JSON payloads without corrupting formatting. **The preeminent TypeScript/JavaScript solution for business document and contract templating.**



- **[gopdf](https://github.com/signintech/gopdf)** [![GitHub stars](https://img.shields.io/github/stars/signintech/gopdf?style=social&color=white)](https://github.com/signintech/gopdf/stargazers)  

  Lightweight, dependency-free Go library for generating custom PDF documents from scratch (MIT); provides native TrueType font embedding, UTF-8 unicode text rendering, image drawing, and precise coordinate placement. **High-performance Go utility for generating high-throughput receipts and billing statements.**



- **[docxtpl (python-docx-template)](https://github.com/elapouya/python-docx-template)** [![GitHub stars](https://img.shields.io/github/stars/elapouya/python-docx-template?style=social&color=white)](https://github.com/elapouya/python-docx-template/stargazers)  

  The most widely adopted open-source DOCX templating engine (LGPL-2.1); design a document in Word, insert Jinja2-like tags ({{ variable }}, {%tr %}, {%p %}), and render it from Python with full formatting preservation. Supports tables, images, headers/footers, and complex structures. **The standard foundation for programmatic DOCX generation**—mature, battle-tested, and available via Debian packages.



- **[Carbone](https://github.com/carboneio/carbone)** [![GitHub stars](https://img.shields.io/github/stars/carboneio/carbone?style=social&color=white)](https://github.com/carboneio/carbone/stargazers)  

  Fast and versatile report generator converting JSON data into PDF, DOCX, XLSX, ODT, and PPTX documents using LibreOffice as a conversion engine (Apache-2.0); features intuitive placeholder syntax and dynamic formatting filters. **Versatile multi-format document reporting engine for Node.js backends.**



- **[docx-templates](https://github.com/guigrpa/docx-templates)** [![GitHub stars](https://img.shields.io/github/stars/guigrpa/docx-templates?style=social&color=white)](https://github.com/guigrpa/docx-templates/stargazers)  

  Template-based Word (.docx) report creation engine for Node.js and browsers (MIT); inserts data, loops, conditionals, dynamic images, and custom JavaScript functions directly into Word templates with a clean markup syntax. **Lightweight and modern JavaScript/TypeScript alternative for template-driven DOCX generation.**



- **[open-pdf-sign](https://github.com/open-pdf-sign/open-pdf-sign)** [![GitHub stars](https://img.shields.io/github/stars/open-pdf-sign/open-pdf-sign?style=social&color=white)](https://github.com/open-pdf-sign/open-pdf-sign/stargazers)  

  Open-source command-line tool and Java library for cryptographically signing PDF documents (Apache-2.0); supports visual signature placement, timestamping (RFC 3161), digital certificates, and PDF/A compliance. **Essential building block for automated legal and enterprise document signature pipelines.**



- **[gpdf](https://github.com/gpdf-dev/gpdf)** [![GitHub stars](https://img.shields.io/github/stars/gpdf-dev/gpdf?style=social&color=white)](https://github.com/gpdf-dev/gpdf/stargazers)  

  Go library for building PDFs from JSON schemas or Go templates; includes ready-made constructors for invoices, reports, and letters; supports **digital signatures, AES-256 encryption, PDF/A conformance**, page merging, and absolute positioning. **Strong for Go-based backend document pipelines** requiring compliance-grade output.



- **[unlawful-assembly](https://github.com/splittist/unlawful-assembly)** [![GitHub stars](https://img.shields.io/github/stars/splittist/unlawful-assembly?style=social&color=white)](https://github.com/splittist/unlawful-assembly/stargazers)  

  Open-source client-side web application for survey-driven document assembly; creators design surveys, upload DOCX templates, map fields visually, and bundle into ZIP packages; end users complete the survey and generate customized DOCX via docxtemplater. TypeScript/Survey.js/docxtemplater stack. **The most complete open-source no-code document assembly workflow**—runs entirely in the browser with no server dependency.



- **[Aldina](https://github.com/clbrge/aldina)** [![GitHub stars](https://img.shields.io/github/stars/clbrge/aldina?style=social&color=white)](https://github.com/clbrge/aldina/stargazers)  

  Open-source engine for producing **on-brand, print-grade documents**—letters, reports, decks, invoices, one-pagers—from content and a theme (AGPL-3.0 with commercial option). Pipeline: ChoirMark → compose into theme grammar → **gate (admit/reject based on fit, contrast, hierarchy)** → project to PDF. Deterministic layout with bounded LLM checkpoints; the gate refuses pages that don't pass hard checks rather than shipping broken output. **The most sophisticated open-source approach to print-quality branded document generation**, with a novel quality-gate architecture.



### Additional Strong Open-Source Options & Libraries

- **[docxtpl-ng](https://pypi.org/project/docxtpl-ng/)** — Independent MIT-licensed reimplementation of docxtpl; uses python-docx-ng and Jinja2 with a typed element tree rather than regex over serialized XML for schema-validated output.
- **[docma](https://pypi.org/project/docma/)** — Python document generator developed at Origin Energy; assembles PDF and HTML documents from templates with dynamic control flow, PDF watermarking, and Vega-lite charts.
- **[pymsword](https://pypi.org/project/pymsword/)** — Python library for DOCX generation with Jinja-like placeholders and group repetition (paragraph, row, cell markers); supports direct DOCX rendering or COM automation.
- **[fullbleed](https://pypi.org/project/fullbleed/)** — Python PDF engine optimized for high-volume variable data printing (VDP); fixed-geometry and reflow bindings rendering hundreds of thousands of distinct invoices per second.
- **[ferropdf](https://pypi.org/project/ferropdf/)** — Fast, self-contained HTML/CSS to PDF renderer built with a Rust core and Python bindings without requiring headless Chromium.

**Frameworks for building custom systems**: Combine **docxtpl**, **docxtemplater**, or **docx-templates** for DOCX template rendering, **Gotenberg** or **WeasyPrint** for HTML-to-PDF microservices, **open-pdf-sign** or **gpdf** for digital signatures and PDF/A compliance, and **Aldina** for quality-gated print documents in a self-hosted document generation stack.



## How to Contribute

1. Fork the repo.
2. Add/edit entries in README.md (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Document generation platforms handling contracts and business data must comply with applicable regulations and organizational governance policies; template versioning and output audit trails are important for legal and financial documents.
- **Open-source document generation is mature at the library level but requires assembly for platform-level capability**—docxtpl, docxtemplater, and Gotenberg provide robust rendering and conversion engines, but organizations requiring an end-to-end platform (governance, advanced approvals, enterprise connectors, signature tracking) often evaluate commercial products or assemble integrated stacks.
- Verify license terms for commercial use (e.g., Apache-2.0, MIT, BSD, LGPL-2.1, AGPL-3.0).

---

**Made for document automation engineers, legal operations teams, finance report builders, and contract lifecycle practitioners.**  
Let's make document generation more open, template-driven, and output-ready.
