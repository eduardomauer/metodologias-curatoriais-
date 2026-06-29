# Codex Guardrails

These rules apply to Codex or any automated coding/documentation agent working on this repository.

## Default mode

The default mode is **read, diagnose and propose**.

No automated tool may assume permission to publish, delete, rewrite or restructure public institutional documentation.

## Hard restrictions

Codex must not:

- work directly on the default branch unless explicitly instructed by a human maintainer;
- delete files;
- rename files or folders;
- change licences;
- change authorship metadata;
- merge Associação MILK, Atlas Vivo MILK, Eduardo Mauer and Nuno A. into one undifferentiated authorial layer;
- publish private Drive material;
- add credentials, tokens, secrets or private configuration;
- add personal data;
- expose protected Atlas/OCSR methods;
- publish restricted assets, photographs or visual works;
- alter RGPD-related language without explicit human review;
- declare compliance, validation, certification or legal sufficiency unless the evidence is present in the repository.

## Permitted tasks

Codex may assist with:

- spelling and formatting corrections;
- README consistency;
- metadata drafts;
- changelog updates;
- governance documentation;
- release checklists;
- citation file validation;
- non-sensitive documentation structure;
- explaining risks before a human decision.

## Required output for every task

Codex must report:

1. files read;
2. files proposed for change;
3. exact diff or final text;
4. what remains intact;
5. regression risk;
6. validation method;
7. human decision required.

## No-regression rule

Validated content must not be weakened, summarised, deleted or replaced with generic language. Improvements must be additive, traceable and reversible.

## Publication rule

If Codex finds any uncertain rights, personal data, private method, restricted visual asset or ambiguous authorship, it must stop and recommend human review instead of attempting automatic publication.
