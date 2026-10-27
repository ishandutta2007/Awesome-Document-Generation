# Awesome-Document-Generation

# Top Document Generation Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Template-Driven Document Assembly, Data Merging & Automated Output*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Document Generation**. These tools enable organizations to automatically produce personalized documents—contracts, proposals, invoices, reports, and letters—by merging structured data into templates, eliminating manual drafting while ensuring brand consistency and compliance.

**Examples** include Workday Document Generation, PandaDoc, DocuSign Gen, Conga Composer, Adobe Acrobat Sign, Nintex DocGen, Formstack Documents, SmartIQ, HotDocs, and airSlate (the category leaders).

**Open-source emphasis**: Document Generation is a domain where open-source tooling is **mature at the library level but fragmented as a complete platform**. The strongest active projects are **docxtpl** (Jinja2 templating for DOCX), **Aldina** (theme-driven print-grade PDF generation with a deterministic gate), and **gpdf** (Go-based PDF generation with digital signatures and PDF/A). For survey-driven document assembly, **unlawful-assembly** provides a client-side no-code workflow. Organizations seeking a complete SaaS-equivalent platform must assemble components or adopt a commercial product.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Workday Document Generation](https://www.workday.com/)**  
  Document generation within Workday's suite for producing formatted output from HR and financial data, integrated with business processes and templates.

- **[PandaDoc](https://www.pandadoc.com/)**  
  Document automation platform combining template-based generation with e-signature, proposals, and contract workflows.

- **[DocuSign Gen](https://www.docusign.com/)**  
  Document generation for Salesforce, enabling template-based contract and agreement creation directly from CRM records.

- **[Conga Composer](https://conga.com/)**  
  Document generation and reporting solution for Salesforce and Microsoft Dynamics, merging data into Word, Excel, PowerPoint, and PDF templates.

- **[Adobe Acrobat Sign](https://www.adobe.com/sign.html)**  
  E-signature platform with document generation and form workflows integrated with Adobe's document ecosystem.

- **[Nintex DocGen](https://www.nintex.com/)**  
  Document generation for Salesforce and SharePoint, producing Word, PDF, Excel, and PowerPoint documents from templates and data.

- **[Formstack Documents](https://www.formstack.com/)**  
  Document automation platform (formerly WebMerge) for generating PDFs, Word docs, and presentations from form submissions and data sources.

- **[SmartIQ](https://www.smartiq.com/)**  
  Intelligent document generation and workflow platform for complex, regulated document assembly.

- **[HotDocs](https://www.hotdocs.com/)**  
  Document assembly and automation software with template authoring, interview-based generation, and integration for legal and financial documents.

- **[airSlate](https://www.airslate.com/)**  
  Document workflow automation platform with e-signature, robotic process automation, and no-code workflow builder.

## Open-Source GitHub Projects

- **[docxtpl (python-docx-template)](https://github.com/elapouya/python-docx-template)**  
  The most widely adopted open-source DOCX templating engine (LGPL-2.1); design a document in Word, insert Jinja2-like tags (`{{ variable }}`, `{%tr %}`, `{%p %}`), and render it from Python with full formatting preservation . Supports tables, images, headers/footers, and complex structures. **The standard foundation for programmatic DOCX generation**—mature, battle-tested, and available via Debian packages.

- **[docxtpl-ng](https://pypi.org/project/docxtpl-ng/)**  
  Independent MIT-licensed reimplementation of docxtpl (Alpha, v0.2.0, 269 tests); uses `python-docx-ng` and Jinja2 with a typed element tree rather than regex over serialized XML; reproduces the same tag dialect exactly and migrates by swapping the dependency . **For teams wanting a permissively licensed, actively modernized docxtpl alternative**—expect rough edges in alpha but schema-validated output.

- **[Aldina](https://github.com/clbrge/aldina)**  
  Open-source engine for producing **on-brand, print-grade documents**—letters, reports, decks, invoices, one-pagers—from content and a theme (AGPL-3.0 with commercial option). Pipeline: ChoirMark → compose into theme grammar → **gate (admit/reject based on fit, contrast, hierarchy)** → project to PDF. Deterministic layout with bounded LLM checkpoints; the gate refuses pages that don't pass hard checks rather than shipping broken output . **The most sophisticated open-source approach to print-quality branded document generation**, with a novel quality-gate architecture.

- **[gpdf](https://pkg.go.dev/github.com/gpdf-dev/gpdf)**  
  Go library for building PDFs from JSON schemas or Go templates; includes ready-made constructors for invoices, reports, and letters; supports **digital signatures, AES-256 encryption, PDF/A conformance**, page merging, and absolute positioning . **Strong for Go-based backend document pipelines** requiring compliance-grade output.

- **[unlawful-assembly](https://github.com/splittist/unlawful-assembly)**  
  Open-source client-side web application for survey-driven document assembly; creators design surveys, upload DOCX templates, map fields visually, and bundle into ZIP packages; end users complete the survey and generate customized DOCX via docxtemplater . TypeScript/Survey.js/docxtemplater stack. **The most complete open-source no-code document assembly workflow**—runs entirely in the browser with no server dependency.

- **[docma](https://pypi.org/project/docma/)**  
  Python document generator developed at Origin Energy; assembles PDF and HTML documents from templates with dynamic content (conditionals, loops, transformations) based on structured data; supports composition of multiple source documents, conditional inclusion, schema validation, PDF watermarking, and Vega-lite charts . **For complex multi-source document composition** with data-driven control flow.

- **[pymsword](https://pypi.org/project/pymsword/)**  
  Python library for DOCX generation with Jinja-like placeholders and group repetition (paragraph, row, cell markers); supports direct DOCX rendering (pure Python) or COM automation for full Word features (requires Word installed) . MIT-licensed. **Lightweight alternative to docxtpl** when you need table row repetition with a simpler API.

- **[fullbleed](https://pypi.org/project/fullbleed/)**  
  Python PDF engine optimized for **high-volume variable data printing (VDP)**; compiled templates render 100,000 distinct invoices in ~284 ms (352k pages/s) for fixed-geometry slots; supports reflow bindings for size-changing records (43.8x speedup over ordinary path) . **For transactional document generation at scale**—invoices, statements, policies—where throughput is the primary constraint.

- **[ferropdf](https://pypi.org/project/ferropdf/)**  
  Fast, self-contained HTML/CSS to PDF renderer (Rust core with Python bindings, MIT/Apache-2.0); not a browser engine—supports a CSS subset (flexbox, tables, box model) with known limitations (no CSS Grid, absolute positioning planned v0.2) . **For lightweight HTML-to-PDF generation** without the overhead of headless Chromium.

### Additional Strong Open-Source Options

- **LOTemplate** — Document generator creating ODT, DOCX, and PDF from DOCX/ODT templates and JSON data; 23 GitHub stars, actively maintained .
- **opendocs** — Converts GitHub READMEs into DOCX, PPTX, PDF, LaTeX, and Jira tickets; useful for documentation generation but not business document assembly .
- **OneDoc** — Developer-oriented document platform for generating, hosting, and tracking PDFs via API; 58 GitHub stars .

**Frameworks for building custom systems**: Combine **docxtpl** or **docxtpl-ng** for DOCX template rendering, **Aldina** for branded print-grade PDFs with quality gates, **unlawful-assembly** for survey-driven no-code assembly, and **fullbleed** for high-volume transactional PDF generation in a self-hosted document generation stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Document generation platforms handling contracts and business data must comply with applicable regulations and organizational governance policies; template versioning and output audit trails are important for legal and financial documents.
- **Open-source document generation is mature at the library level but requires assembly for platform-level capability**—docxtpl and gpdf provide robust rendering engines, Aldina provides quality-gated output, but no single open-source project delivers the full SaaS experience (template management, data connectors, workflow, e-signature) of PandaDoc or Conga. Organizations requiring an end-to-end platform should evaluate commercial products or plan for integration work.
- Verify license terms for commercial use; docxtpl uses LGPL-2.1 , docxtpl-ng uses MIT , Aldina uses AGPL-3.0 with commercial option , and gpdf is open-source .

---

**Made for document automation engineers, legal operations teams, finance report builders, and contract lifecycle practitioners.**  
Let's make document generation more open, template-driven, and output-ready.
