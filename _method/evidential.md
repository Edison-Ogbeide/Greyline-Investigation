---
title: "Evidential"
slug: evidential
description: "Chain of custody, capture tooling, admissibility, and how evidence is preserved and handed over, the standard every Greyline deliverable is built to."
crumbs:
  - title: "Method"
    url: /method/
  - title: "Evidential"
    url: /method/evidential/
---
### The Principle

Every piece of evidence Greyline collects is handled to a documented chain of custody from the moment it is captured. Original data is never altered. Capture tools log hash values, timestamps, and provenance automatically. Any subsequent handling is recorded in a contemporaneous log an independent third party could reproduce.

This standard applies from the first day of the engagement, not retrofitted once litigation becomes likely. Retrofitting evidential rigour after the fact is usually the point where a finding stops being defensible.

<hr class="gold-rule">

### ACPO Principles for Digital Evidence

Greyline's digital evidence work is conducted to the **ACPO Principles for Digital Evidence** (now maintained by the College of Policing):

1. **No action taken by law enforcement agencies or their agents should change data held on a computer or storage media which may subsequently be relied upon in court.**
2. **In exceptional circumstances, where a person finds it necessary to access original data held on a computer or storage media, that person must be competent to do so and be able to give evidence explaining the relevance and the implications of their actions.**
3. **An audit trail or other record of all processes applied to computer-based electronic evidence should be created and preserved. An independent third party should be able to examine those processes and achieve the same result.**
4. **The person in charge of the investigation has overall responsibility for ensuring that the law and these principles are adhered to.**

We apply these principles regardless of whether the engagement is litigation-aligned. They are our baseline, not a premium add-on.

<hr class="gold-rule">

### Capture and Preservation

**Screenshots and web captures**: Taken using forensic capture tools that record URL, timestamp, and hash value automatically. Where possible, captures are made via independent archiving services to create a third-party timestamped record.

**Documentary evidence**: Scanned or photographed with metadata preserved. Originals are retained where instructed and a receipt is issued.

**Digital forensic images**: Created using write-blocking hardware and forensic imaging software. Each image is accompanied by a cryptographic hash (MD5 and SHA-256) to verify integrity.

**Communication records**: Preserved in native format where possible, with metadata intact. Transcripts are verified against originals.

<hr class="gold-rule">

### Chain of Custody Documentation

For every item of evidence, the following is recorded:

- **What** was collected
- **When** it was collected (date and time, timezone-aware)
- **Where** it was collected from (URL, platform, device identifier)
- **How** it was collected (tool, method, any access credentials used)
- **By whom** (named analyst)
- **What has happened to it since** (storage location, transfers, analysis steps)

This record is maintained in Greyline Sentinel, our internal case management platform, and is available for inspection by the client or their legal representatives on request.

<hr class="gold-rule">

### Admissibility and Litigation Alignment

Where a deliverable may end up in front of a court, a family financial disclosure dispute, a defamation claim, a fraud recovery action, the same evidence standard applies from day one.

For litigation-aligned engagements, we provide:

- **Chain-of-custody documentation** as standard
- **CPR Part 35 compliant** report formatting where the instruction calls for it
- **Expert witness statement** preparation where required
- **Disclosure-ready** evidence bundles with index and provenance notes

We do not wait for a dispute to become adversarial before we start acting like it might. By then, it is usually too late.

<hr class="gold-rule">

### Handover

Evidence is handed over to a client, solicitor, or court following a documented process:

1. **Inventory**: A complete list of what is being handed over, with unique identifiers.
2. **Provenance**: How each item was collected, by whom, and when.
3. **Integrity verification**: Hash values or other integrity checks so the recipient can confirm the evidence has not been altered since collection.
4. **Receipt**: Signed acknowledgement of transfer, creating the next link in the chain of custody.

This process ensures that evidence collected by Greyline can be relied upon by the client and, where necessary, by a court.

<hr class="gold-rule">

### What This Means for the Client

You receive evidence that is:
- **Defensible**: Collected and handled to a standard that will withstand scrutiny.
- **Traceable**: Every item can be traced back to its source, its collector, and its collection method.
- **Reproducible**: An independent third party can follow our documented process and arrive at the same result.
- **Transferable**: Handed over in a format that maintains its integrity and provenance.

This is not an optional extra. It is the standard against which every Greyline report is written.
