---
title: "Technology"
slug: technology
description: "The named tool stack behind Greyline's analysis, and the platform layer, Greyline Sentinel, live today, and the Greyline Intelligence Cloud, on our roadmap."
crumbs:
  - title: "Method"
    url: /method/
  - title: "Technology"
    url: /method/technology/
---
### Tooling as Enabler, Not Replacement

Greyline's analysts work with a defined stack of licensed OSINT, forensic, and monitoring tooling. These tools accelerate collection and cross-referencing. They do not replace analyst judgement, and they do not sign off findings.

Every tool in the stack is selected and maintained to the evidential standard described throughout this section. If a tool cannot produce output that meets our chain-of-custody and reproducibility requirements, we do not use it for evidential work.

<hr class="gold-rule">

### The OSINT and Investigation Stack

Our analysts use a curated set of licensed platforms and tools for:

- **Open-source collection**: Advanced search, archive retrieval, public record aggregation
- **Social media analysis**: Platform-native research, network mapping, temporal analysis
- **Dark web monitoring**: Structured access to dark web markets, forums, and threat-actor channels
- **Geolocation and imagery analysis**: Reverse image search, metadata extraction, geolocation verification
- **Network and infrastructure analysis**: Domain and IP research, threat-actor infrastructure mapping
- **Entity resolution**: Cross-referencing identifiers across disparate sources

We do not rely on free tools for evidential work where a licensed, auditable alternative exists. The provenance of our tooling matters as much as the provenance of our evidence.

<hr class="gold-rule">

### Forensic and Capture Tooling

For digital evidence collection, we use:

- **Forensic imaging tools**: Write-blocked acquisition with cryptographic hashing
- **Capture and archiving tools**: Automated URL, timestamp, and hash logging
- **Metadata preservation tools**: Ensuring EXIF, header, and file system data remains intact
- **Secure storage**: Encrypted at rest, access-logged, UK-jurisdiction infrastructure

All forensic tooling is maintained, version-controlled, and documented. If a court asks what tool produced a given image and how it works, we can answer.

<hr class="gold-rule">

### Greyline Sentinel

**Greyline Sentinel** is our internal platform for structured collection and case management. It is the system our analysts use today to:

- **Log sources**: Every source consulted is recorded with date, analyst, and reliability grade.
- **Timestamp evidence**: Automated timestamping of captures and collection actions.
- **Maintain chain of custody**: The full audit trail from collection to report is held in Sentinel, exportable on request.
- **Manage case workflow**: From intake through scoping, investigation, and delivery, case stages are tracked and documented.
- **Support reproducibility**: An independent third party can follow the Sentinel record and reproduce our process.

Sentinel is not a client-facing platform. It is the operational backbone that ensures the standard is met on every engagement.

<hr class="gold-rule">

### Greyline Intelligence Cloud

**Greyline Intelligence Cloud** is on our product roadmap. It is a planned extension of Sentinel for clients who want ongoing, structured visibility into a live monitoring engagement.

**What it is not**: It is not yet built. It is not available to instruct. We are naming it here so the direction of travel is transparent, not to describe a live capability or a plan a client can currently sign up to.

**What it is intended to be**: A client-accessible layer for ongoing engagements, threat monitoring, brand surveillance, executive protection, where the client needs real-time visibility into what we are seeing and how we are assessing it.

When Intelligence Cloud moves from roadmap to live product, this page will be updated with full technical and security specifications.

<hr class="gold-rule">

### AI and Automation: Our Position

We use AI-assisted tools in two contexts:

1. **Collection assistance**: Pattern-matching, candidate surfacing, large dataset triage. The AI flags; the analyst verifies.
2. **Synthetic intelligence detection**: Probabilistic detection of AI-generated content, deepfakes, and synthetic media. Findings are worded as *consistent with* synthetic generation, not *proof of* it.

In both cases, the analyst's verification is mandatory and documented. We do not use generative AI to write findings, to draft reports, or to reach analytical conclusions. The accountability chain runs from the evidence, through the analyst, to the named signatory. AI is not in that chain.

<hr class="gold-rule">

### Data Security and Jurisdiction

All case data is held on **UK-jurisdiction infrastructure**. Data is:

- **Encrypted in transit** (TLS 1.3 minimum)
- **Encrypted at rest** (AES-256)
- **Access-controlled** on a need-to-know basis, logged and auditable
- **Retained** only for the period required by the engagement terms and applicable law
- **Deleted** securely on request or at the end of the retention period, with confirmation provided

We do not store client data on cloud infrastructure outside UK or EEA jurisdiction without explicit client consent and a documented legal basis.

<hr class="gold-rule">

### What This Means for the Client

You engage a firm where:
- **Tools are auditable**: Licensed, maintained, documented, and selected for evidential rigour.
- **Platforms support accountability**: Sentinel ensures the chain of custody is maintained automatically, not reconstructed from memory.
- **AI is governed**: Used only where it assists collection, never where it replaces judgement, and always with mandatory analyst verification.
- **Data is secure**: UK-jurisdiction, encrypted, access-controlled, and retained only as necessary.
