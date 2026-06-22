# Forgejo, Zenodo and Software Heritage Pipeline

## Chain

1. Internal working archive.
2. Public-safe files in canonical forge.
3. Immutable tag.
4. Checksums and release notes.
5. Zenodo deposition API.
6. Software Heritage archive and SWHID.
7. Citation metadata update.

## Required outputs

- CITATION.cff
- codemeta.json
- .zenodo.json
- metadata/datacite.json
- metadata/dcat.json
- metadata/provenance.json
- metadata/checksums/MANIFEST_SHA256.txt

Status: specification only until final release.
