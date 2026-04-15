# Contributing to Primary / Humming Box Problem

**Thank you for your interest.** This repository is unusual — it's a cryptographic provenance declaration and a philosophical essay, not a software library or traditional open-source project.

Please read this before opening issues, pull requests, or discussions.

## What This Repository Is

- A **public declaration of authorship** under the Lineage-Primary framework
- A **cryptographic manifest** (SHA-256 hashes) anchoring private source materials
- A **philosophical essay** on the Humming Box Problem and digital continuity
- A **living discussion space** about meaning drift, preservation failure, and provenance

## What This Repository Is NOT

- ❌ A software library with installable packages
- ❌ A framework with runnable code (yet — this may evolve)
- ❌ A place to host or distribute the protected source materials
- ❌ A general-purpose preservation tool

## Ways You Can Contribute

Even without code, your contributions are valuable:

### 1. Open a Discussion or Issue

The README explicitly invites conversation about the Humming Box Problem. Good topics include:

- Real-world examples of **meaning drift** (bits intact, context lost)
- Counter-examples that challenge or refine the framework
- Case studies from archives, research data, software archaeology, or digital art
- Technical approaches to tracking **lineage** and **continuity**
- Connections to existing standards (PROV-O, PREMIS, OAIS, etc.)

**Before opening an issue:**
- Search existing issues to avoid duplicates
- Be specific — reference times, places, systems where possible
- Connect your example to the core idea: *identity survives through continuity, not static preservation*

### 2. Suggest Clarifications to the README or Manifest

If something in `README.md`, `MANIFEST.md`, or `PROVENANCE_STATEMENT.md` is unclear, please open an issue with the label `documentation`.

**Examples:**
- Ambiguous phrasing in the Humming Box essay
- Missing verification instructions for the manifest
- Legal or attribution questions

### 3. Propose Extensions to the Framework

The Lineage-Primary framework is in early form. If you have ideas for:

- Machine-readable lineage formats (JSON-LD, YAML manifests)
- Verification tooling (scripts, CLIs)
- Integration with Git, IPFS, or blockchain timestamping
- Formalizing the "8PF" concept (if that becomes public)

…please open a **discussion** first, not a pull request. Major changes need conceptual alignment.

### 4. Report Errors

If you find a factual error, broken link, or inconsistency in the repository:

- Open an issue with label `bug`
- Include the exact file and line number (GitHub allows permalinks)

## What Does NOT Belong Here

The following will be closed without discussion:

- Requests for access to the private source materials (they are not distributed)
- Legal challenges to the authorship claim (the cryptographic manifest is the evidence)
- Off-topic promotion of commercial products
- Spam, harassment, or anything violating the `CODE_OF_CONDUCT.md`

## Pull Requests

Because this repository is primarily a **declaration**, pull requests are **rarely accepted** unless they are:

- Trivial typo fixes in non-legal files (e.g., README)
- Additions to the `.gitignore` or repository metadata
- Suggestions that have first been approved via a discussion issue

**For any substantial change:**
1. Open a discussion issue first
2. Wait for maintainer response
3. If approved, submit a pull request referencing the issue

**Why so restrictive?**  
The cryptographic manifest (`MANIFEST.md`) and legal files (`COPYRIGHT.md`, `LICENCE`, `PROVENANCE_STATEMENT.md`) anchor a public claim of authorship. Changing them without careful review undermines the provenance model.

## Setting Up for Local Verification (Optional)

If you want to verify the cryptographic manifest against the repository state:

```bash
# Clone the repository
git clone https://github.com/mmke01404-collab/Primary.git
cd Primary

# Verify a specific file against its hash in MANIFEST.md
# Example: Check README.md
sha256sum README.md
# Compare output to the hash listed in MANIFEST.md
