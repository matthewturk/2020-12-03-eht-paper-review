<!-- .slide: class="titleslide" -->

# Paper Reviewing System

## Matthew Turk

<p data-markdown=true><tt>mjturk@illinois.edu</tt></p>

---

## Current System

 * Largely email-based
 * Each step in workflow is mediated by humans
 * Scalability is in question, as is accessibility

---

## Categories of Paper

 * "Collaboration" papers
 * "Official" papers
 * "Related" papers
 * "Unrelated" papers

---

## Current Workflow

1. Papers circulated by email
2. Reviewers identified manually and invited manually
3. Manual recirculation of new versions

---

## Options

 1. Retrofit a paper review system into existing collaboration tools
 2. Implement new system from scratch
 3. Implement new system from publication review platform

---

## Requirements

 * Minimum barrier to entry for internal users
 * Secure against intrusions and data leakage
 * Permanent storage of multiple revisions
 * Collect internal and external review data
 * Notifications

---

## Existing Collaboration Tools

 * Square peg + round hole
 * Development time would be completely uncertain
 * Rapidly run into API limitations (and limits)
 * Would centralize notifications and communication

---

## New System from Scratch

 * Potential project for enterprising student
 * Could tailor to meet needs
 * Conversely, tailoring to meet needs would require extensive development
 * Security and maintenance would both be challenging

---

## Proposal: Mayan-EDMS

[Mayan EDMS](https://www.mayan-edms.com/) is a document management system used
for tracking, storing and versioning documents.

 * Manages document revisions
 * Classification into "cabinets" and "tags"
 * Ingestion from upload, email and "watched" folder
 * Commenting system next to documents
 * Workflows can be implemented for documents, specific to type

---

## Demo

---

## Some Shortcomings

These are shortcomings I was able to identify in the time I evaluated it.  That does not mean solutions do not exist -- just that I didn't yet figure them out!

 * Anonymity may not be built-in
 * Some components will require configuration: workflows, sources, roles and metadata
 * It may be designed for a scale much larger, with messier documents, than the EHT requires

---

## Infrastructure Needs

 * Easy and extensible storage
 * Minimum system administration effort
 * Straightforward "upgrade" process

---

## Steps

 * Identify deployment platform
 * Implement LDAP-backed SSO
 * Configure SMTP and POP3/IMAP ingest
 * Develop document and paper ontology

---

<!-- .slide: class="titleslide" -->

# Thank you!
