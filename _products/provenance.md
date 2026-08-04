---
title: "Provenance: Media Authenticity Assessment"
slug: provenance
description: "Fixed-scope assessment of contested audio, video and image files, with findings expressed to a standard suitable for litigation."
standfirst: "A structured assessment of whether a contested recording, image or file is what it is presented to be."
what_this_is:
  - "Where a recording or image is disputed, the question is rarely answerable with a simple yes or no. A finding needs to explain what was tested and why it points where it does."
  - "The assessment examines integrity and origin: file metadata, container and encoding history, and content credentials where present. It also reviews evidence of re-encoding or editing, device and codec consistency, and internal plausibility. Findings are expressed as consistent with, not consistent with, or indeterminate, with the reasoning and its limits stated in full."
  - "Two engagement modes are available, Standard and Litigation, set out below."
service_categories:
  - name: "Image Verification"
    intro: "Applied to a contested photograph, screenshot, or still image."
    table_headers: ["Verification Area", "What We Examine"]
    table_rows:
      - ["Metadata and EXIF data", "Camera model, capture date, GPS data, and editing software signatures"]
      - ["Reverse image search", "Prior appearances, stock or stolen content, and earlier versions"]
      - ["Compression and artefact analysis", "Signs of re-encoding, cloning, or splicing"]
      - ["Lighting and shadow consistency", "Physical plausibility of light sources and shadows"]
      - ["Facial and object consistency", "Anatomical or geometric inconsistencies associated with synthetic generation"]
      - ["Content credentials", "Embedded provenance signals where present"]
  - name: "Video Verification"
    intro: "Applied to a contested video clip or recorded call."
    table_headers: ["Verification Area", "What We Examine"]
    table_rows:
      - ["Frame-by-frame analysis", "Temporal consistency across frames"]
      - ["Compression history", "Evidence of re-encoding, transcoding, or multiple exports"]
      - ["Audio-visual synchronisation", "Alignment between lip movement and the audio track"]
      - ["Motion and physics plausibility", "Consistency of movement with physical expectation"]
      - ["Source and container metadata", "Codec, container format, and editing software traces"]
      - ["Synthesis indicator screening", "Known artefacts associated with face-swap and synthetic media tooling"]
  - name: "Audio Verification"
    intro: "Applied to a contested voice recording, voicemail, or call."
    table_headers: ["Verification Area", "What We Examine"]
    table_rows:
      - ["Spectral analysis", "Frequency patterns inconsistent with natural speech or splicing"]
      - ["Voice sample comparison", "Comparison against a genuine voice sample of the claimed speaker, where available"]
      - ["Background consistency", "Ambient noise and acoustic environment plausibility"]
      - ["Compression artefacts", "Evidence of re-recording or synthetic generation"]
      - ["Vishing pattern cross-reference", "The circumstances checked against known social engineering scripts"]
    note: "Where a submission is a suspicious call or voice message rather than a standalone clip, the circumstances are cross-referenced against documented vishing patterns as a matter of course, since a genuine voice can still be used in a scripted deception."
mode_compare:
  - name: "Standard"
    deliverable: "Written assessment with reasoning and stated limitations"
    use: "Internal decision-making, HR, insurance, pre-action"
    availability: "Written clarification"
  - name: "Litigation"
    deliverable: "Report prepared to the standard required of expert evidence, including duty declaration, range of opinion and statement of truth"
    use: "Filed evidence, rebuttal of an opponent's exhibit"
    availability: "Availability to answer questions on the report"
included:
  - "Assessment of file integrity, metadata and encoding history"
  - "Review of content credentials and provenance signals where present"
  - "Analysis of editing, re-encoding and compression artefacts"
  - "Assessment of internal consistency, including acoustic and physical plausibility"
  - "Written findings with reasoning, confidence and stated limitations"
excluded:
  - "A binary determination that content is or is not artificially generated"
  - "Speaker identification or voice attribution to a named individual"
  - "Recovery, extraction or acquisition of files from a device"
  - "Assessment of re-recorded or screen-captured material where original files are unavailable, unless expressly agreed in scope"
who_for:
  - "Solicitors and barristers in family, employment and civil matters, insurers, and in-house counsel most commonly instruct this work. Individuals responding to a contested recording also instruct it directly."
how_it_runs:
  - "Source files are submitted through a confidential inquiry, along with the question the assessment needs to answer."
  - "The engagement mode, Standard or Litigation, is confirmed at scoping, along with turnaround."
  - "Metadata, encoding history, content credentials and internal consistency are examined against the original files."
  - "Findings are reviewed by the principal and expressed as consistent with, not consistent with, or indeterminate, with reasoning stated in full."
  - "The report is delivered. Written clarification, or availability to answer questions under the Litigation mode, follows afterward."
illustrative_examples:
  intro: "The following are illustrative examples of how Provenance is typically used, not accounts of specific client engagements."
  items:
    - title: "Contested recording in a family matter"
      body: "A party to a family dispute submits an audio recording said to capture an admission by the other side. Provenance assesses the file for splicing, re-recording and compression artefacts before either party relies on it in negotiation or proceedings."
    - title: "Workplace investigation"
      body: "An employer receives a video alleged to show misconduct by an employee. Provenance assesses the file's integrity and internal consistency before it informs a disciplinary decision."
    - title: "Insurance claim review"
      body: "An insurer receives photographic evidence supporting a claim. Provenance checks the metadata, compression history and internal consistency of the image before the claim is assessed further."
    - title: "Rebutting an opponent's expert evidence"
      body: "An opposing party serves an expert report relying on a contested image. Under the Litigation mode, Provenance independently re-examines the same file and tests the opposing report's methodology and conclusions."
delivery_note: >-
  Turnaround for a single-file assessment is three working days from receipt
  of usable source material, not from the date of instruction. Volume or
  format complexity may extend this; any extension is agreed in writing
  before work proceeds.
cadence:
  shape: "Fixed scope"
  cadence: "Single engagement"
  deliverable: "Written authenticity assessment, Standard or Litigation mode"
  review: "Principal-reviewed before release"
deliverable_structure:
  - section: "Instructions and issues addressed"
    content: "The specific questions the examination was asked to address"
  - section: "Scope of the examination"
    content: "What was examined, what was not, and which engagement mode applies"
  - section: "Summary of conclusions"
    content: "A short-form answer to each question, ahead of the full reasoning"
  - section: "Exhibit schedule"
    content: "Every item examined, with format, size and hash on receipt"
  - section: "Provenance of the material"
    content: "How each exhibit reached this firm, and what that means for what can be concluded"
  - section: "Chain of custody"
    content: "Full handling record from receipt to examination"
  - section: "Methodology"
    content: "The examination sequence followed and the standards it aligns with"
  - section: "Findings"
    content: "What was observed in each exhibit, by analysis stream"
  - section: "Automated detector outputs"
    content: "Classifier results, with published error rates and their limitations"
  - section: "Evaluation"
    content: "Every anomaly weighed against the innocent explanations considered for it"
  - section: "Conclusions"
    content: "The instructed questions answered, in defined terminology"
  - section: "What would change these conclusions"
    content: "The further material that would allow a firmer answer"
  - section: "Limitations"
    content: "What the examination does, and does not, establish"
  - section: "Declaration"
    content: "The examiner's confirmations, including independence and completeness"
specimen_report:
  path: /media/provenance/specimen-report.pdf
  note: "The specimen below shows a full Standard-mode report, illustrating the report structure above section by section. The case, the exhibits, the parties and every finding are fictitious."
limitations_intro: "Assessment of contested media carries real limits, stated here rather than left implicit."
limitations:
  - "Detection tooling is probabilistic, and its reliability degrades with compression, re-encoding and platform transmission. An indeterminate finding is a legitimate outcome and is reported as such."
  - "Assessment quality depends on access to the original file. Screenshots, forwarded copies and screen recordings materially limit what can be established."
  - "Turnaround runs from receipt of usable source material, not from the date of instruction."
  - "The Litigation mode describes the standard the report is prepared to. It does not, on its own, state the preparing analyst's expert accreditation or courtroom experience; that is confirmed separately where it is relevant to a specific instruction."
crumbs:
  - title: "Products"
    url: /products/
  - title: "Greyline Provenance"
    url: /products/provenance/
---
