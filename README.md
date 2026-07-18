# Lamina | Product Overview

<br>

*Bringing Version Control to Solar*

<br>

<p align="center">
  <a href="https://youtu.be/z3lXZdVrZb8">
    <img src="assets/lamina-demo-project-thumbnail.png" alt="Lamina Product Overview Video" width="70%">
  </a>
  <br>
  <em>90-second demo overview of Lamina</em>
</p>

<br>

## The Problem
Utility-scale solar sites are documented in pieces. Those pieces don't talk to each other.

A Single Line Diagram (SLD) is drawn once, typically as-built at commissioning. A Bill of Materials (BOM) is written separately, often by a different team, at a different time. As the site ages, maintenance logs record what's actually been repaired, replaced, or reconfigured, but that record lives in isolation too, rarely making its way back into the original SLD or BOM.

The result: three sources of truth, each fragmented and frozen at a different moment, none of them reconciled with the others.

Over time, this gap compounds. A component fails and gets replaced, the maintenance log says so, but the SLD still shows the original part. A discrepancy between the SLD and BOM goes unnoticed at commissioning and is never corrected. Multiply this across hundreds of transformers, inverters, and combiner boxes over a site's operating life, and the honest answer to "what does this site actually look like right now?" stops being a simple lookup, it becomes an investigation.

That investigation is expensive. It slows down maintenance, complicates audits, creates risk during ownership transfers, and means asset managers are often making decisions on data that was accurate once, but isn't anymore.

**Lamina exists to close that gap.**

<br>

## How Lamina Works
1. Ingest what you already have.
SLDs, BOMs, and maintenance logs — as PDFs, scanned drawings, or spreadsheets, in whatever format they currently exist. Lamina reads them directly using vision-language models and OCR, with no manual re-entry required.
2. Reconcile the sources against each other.
Documents are cross-referenced against one another as they're read. Where sources agree, that data is trusted. Where they conflict — or where a component appears in one source but not another — it's surfaced for a human to confirm the correct value. This keeps onboarding fast, without asserting certainty the extraction doesn't actually have.
3. Build one structured registry.
Reconciled data is written into a relational database that preserves the site's real electrical hierarchy: transformers → inverters → DC combiners → strings. The output isn't a document — it's a live, queryable model of the site as it actually stands.
4. Maintain the registry.
Standard maintenance practices now maintain the underlying registry. Logging visits, repairs, and replacements automatically keeps site documentation up to date and prevents data drift, without a new dedicated workflow.

### Features Built on the Registry

- **Topology view:** a navigable map of the site's full electrical structure, down to individual component specs.
- **Live bill of materials:** reflects the current registry state, configurable exports on demand. Export specific sub-sections
- **Discrepancy log:** flags source conflicts at the point of ingestion. Resolve to build an accurate database.
- **Issue flagging:** ties a real-world concern (a failing inverter, damaged fencing) directly to the affected component, notified to the team.
- **Maintenance logging:** records visits, repairs, and replacements against the registry. A maintenance log which maintains the accuracy of all datasources keeping the as-built record aligned with what's actually installed.
- **Historical database:** changes are recorded, not overwritten, every update to the registry preserves what came before. View the site as it is now, or reconstruct its state at any point in time. Version control for physical infrastructure.

*Future Expansions and Features also Planned*
