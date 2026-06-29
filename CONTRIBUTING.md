# Contributing Rules

This repository accepts only public, reviewed and non-sensitive curatorial documentation.

## Before contributing

Do not add material unless it is clear that it may be public.

A contribution must not include:

- credentials, tokens, OAuth secrets or API keys;
- personal data;
- private correspondence;
- unpublished contracts;
- restricted Atlas Vivo MILK methodology;
- internal OCSR analytical layers;
- confidential strategy;
- unlicensed images or photographs;
- protected visual assets;
- unvalidated testimonies;
- content whose authorship, provenance or licence is unclear.

## Required metadata

Every new public file should include, either in the file itself or in a related metadata file:

- title;
- responsible entity or author;
- date;
- version;
- access level;
- licence or reuse condition;
- validation status;
- source or provenance;
- relation to Associação MILK, Atlas Vivo MILK or Eduardo Mauer, when applicable.

## Branch rule

Use a dedicated branch for every substantial change.

Recommended branch format:

```text
area/topic-YYYYMMDD
```

Examples:

```text
docs/governance-20260629
docs/provenance-20260629
metadata/codemeta-20260629
```

## Review checklist

Before merging, confirm:

- the default branch is not being modified blindly;
- the diff is understandable;
- no sensitive material was added;
- no validated text was removed without explicit reason;
- no authorship layer was merged incorrectly;
- the licence statement is compatible with the file;
- the change supports public documentation, citation, accessibility, interoperability or governance.

## Automated tools

Automated tools may assist with formatting, metadata, documentation and consistency checks. They must not be treated as final validators of legal, ethical, curatorial, authorship or publication decisions.

Any automated change must be reviewed by a human before merge.
