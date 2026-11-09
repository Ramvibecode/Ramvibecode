# Ramakrishnan Mallichettiar

**Supply Chain Operations | ERP & EDI | Business Process Automation**

Coimbatore, India · Remote

I bring 14+ years of experience across sourcing, procurement, e-commerce fulfillment, international logistics, and operations systems. I work between the people who run the process and the software that supports it: map the workflow, define the controls, make exceptions visible, and help deliver practical tools.

## Selected work

### Emboss ERP — Operations and logistics workflows

Operations and ERP process work for Emboss Design. I translate purchasing, international logistics, customs, invoicing, and AP/AR requirements into workflows that make each record traceable, expose exceptions early, and keep people in control of consequential actions.

#### Purchase orders, shipments, and exception control

- Match purchase orders to shipment and forwarder data, normalize status updates, and make the current milestone visible in one operational view.
- Track shipment events such as departure, arrival, appointments, warehouse delivery, gate-out, and empty return.
- Separate matched and unchanged records from unmatched, ambiguous, duplicate, or invalid updates so exceptions can be reviewed without silently changing the wrong order.
- Surface missing documents, release or appointment gaps, delayed arrivals, delivery deadlines, and the next follow-up needed.

#### AP documents and customs records

- Route invoice and logistics attachments from Outlook and SharePoint into a PO-centered document workflow, with duplicate checks and a path for unclassified documents.
- Classify likely invoices while sending uncertain records to human review; prepare structured AP intake data for review before import.
- Keep customs entry files and Form 7501 details linked to their supporting records, with a master-register process for approved updates and follow-up on missing information.

#### Invoicing, freight, and cost controls

- Support separate Goods, Freight, and Tariff invoice workflows, including brand-aware invoice preparation where one order contains multiple brands.
- Allocate freight using explicit line-level amounts and reconcile the allocation to the freight total before an invoice can proceed.
- Compare expected and actual costs, flag variances, and catch missing or inconsistent inputs before they reach a customer-facing document.
- Preserve correction and duplicate-draft history while preventing parent drafts or repeated records from being counted twice.

#### Review and communication boundaries

- Use duplicate safeguards, idempotent synchronization, audit history, and visible exception states to make operational changes reviewable.
- Keep external email actions draft-only so a person can inspect and approve a message before it is sent.
- Use human review before uncertain AP imports or other material updates.

**My role:** ERP and operations process ownership, requirements, workflow and data-rule design, exception handling, UAT, and AI-assisted implementation.

**Tools:** Supabase/PostgreSQL, Cloudflare Pages and Workers, JavaScript, SharePoint, Outlook, Power Automate, REST APIs, and structured CSV/JSON data.

Internal source code, customer/vendor details, and live business records are not included.

### Real Essentials — E-commerce Operations Toolkit

Built and maintained a browser-based operations hub for supplier, NetSuite, and Amazon marketplace workflows. It brings recurring file preparation, validation, matching, and exception review into a connected set of focused tools.

#### Supplier files, NetSuite purchase orders, and inbound reconciliation

- **Inbound Processor** accepts a single supplier invoice or packing list, or a batch of documents, and prepares them for PO-backed processing.
- **NetSuite API connection:** the tool reads the relevant purchase-order data from NetSuite through an authorized API connection, then matches uploaded documents against the available PO and item records.
- **Quantity and carton checks:** compare invoice and packing-list quantities with the PO, including carton or case quantities, and surface missing, excess, or inconsistent details before reconciliation.
- **Inbound creation and update:** for a valid match, create or update the corresponding inbound shipment record in NetSuite from the RE workflow.
- **Exception routing:** isolate records that fail matching or validation and automatically notify the responsible internal team, such as Inventory, by email.
- **Confirmed reconciliation:** after the team confirms the correct PO and inbound, reconcile the exception to that specific inbound shipment and update its NetSuite record. This keeps errors from being silently applied to the wrong inbound.

#### Amazon FBA preparation and shipment checks

- **Send to Amazon** organizes and validates shipment inputs, including item, carton, and manifest information, before the FBA workflow proceeds.
- **FBA Order List** consolidates order and shipment records for operational review.
- **FBA Shipped Qty Cross-Check** compares expected and shipped quantities and highlights discrepancies that need investigation.

#### Catalog quality and Seller Central follow-up

- **Flat File Toolkit** checks marketplace listing files for required structure and data issues before upload.
- **Listing Compare** compares listing records to find missing, changed, or mismatched product information.
- **Case Tracker** keeps Seller Central cases and their follow-up actions visible.

#### Direct API integration direction

The toolkit’s documented workflow is file-driven. The next integration layer is to move approved actions into the workspace through authorized APIs:

- Use Amazon’s **Selling Partner API (SP-API)** for supported seller and FBA operations, including creating and managing inbound plans and shipments, then retrieving related shipment information and documents.
- Use the separate **Amazon Ads API** for advertising operations such as campaign creation and management. Advertising uses its own API access and permissions; it is not part of the Selling Partner API.
- A future direct NetSuite connector could replace exported PO files with authorized system-to-system exchange.

These API connections require the relevant account authorization, permissions, and implementation. The public case study distinguishes the existing file-based toolkit from this planned integration scope.

The original HTML and company data are not published.

### Glassworks Workroom — CRM-style operations prototype

A public single-file prototype built with fictional sample data. It brings recruitment, onboarding, retail training, stock movements, tasks, SOPs, AI workflow templates, and reporting into one workspace.

[View the public project](https://github.com/Ramvibecode/glassworks-workroom)

## Automation across roles

- Supplier, purchase order, production, and inbound workflows
- Shipment document intake, matching, milestone tracking, and exception queues
- Invoice, freight, customs, and landed-cost reconciliation
- Outlook and SharePoint document workflows with human review
- E-commerce fulfillment, FBA preparation, catalog checks, and shipment quantity audits
- SOPs, UAT, management reporting, and workflow adoption

## Skills

**Supply chain and e-commerce:** Procurement, supplier negotiation, production coordination, PO management, inventory planning, international freight, customs, 3PL and warehouse operations, Amazon FBA, marketplace fulfillment, EDI, landed cost, AP/AR support.

**ERP and operations systems:** Process mapping, requirements, workflow design, reconciliation, exception handling, approval boundaries, audit history, SOPs, UAT, and operational reporting.

**Automation and AI:** Power Automate, n8n, Make, Zapier, AI-assisted document extraction and classification, human-in-the-loop review, ChatGPT, Claude, and Codex.

**Data and implementation:** JavaScript, Python, REST APIs, webhooks, JSON/CSV, Supabase/PostgreSQL, Cloudflare Pages/Workers, Git/GitHub, SharePoint, Outlook, and Excel.

**Business systems:** NetSuite, CIN7, SPS Commerce/EDI, Amazon Seller Central, Power BI, QuickBooks, and SAP exposure.

## Experience

- **Senior Business Support Manager — Real Essentials / RE Brands** (2024–present)
- **Operations and Systems Project Work — Emboss Design LLC**
- **Transport Manager / Administrator — IDKIDS Community / Confiar Consultants** (2022–2024)
- **E-commerce Manager — Nirmala Tex** (2020–2022)
- **Vendor Manager — Teremac Private Limited / Texfy.com** (2017–2020)
- **Merchandiser — Centrale D’Achats Zannier** (2012–2017)
- **Junior Merchandiser — Geethalaya Exports** (2010–2012)

## Education

**Bachelor of Computer Applications** — RVS College of Arts and Science, Bharathiar University

---

I’m interested in remote and freelance work in supply-chain operations, ERP/EDI, e-commerce fulfillment, and business process automation.