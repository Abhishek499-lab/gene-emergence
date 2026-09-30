# Repository Provenance

## Purpose

This repository is a curated public-release version of the GENE EMERGENCE computational project.

It preserves selected final computational evidence and analysis code without distributing the complete multi-gigabyte working directory.

---

## Source selection

The curated release contains:

- 4 selected analysis/provenance scripts
- 23 final reproducibility files
- final master results
- final claims
- manuscript results tables
- validated sequence datasets
- matched sequence/model tables
- paired-feature datasets
- mechanistic tables
- null distributions
- ancestral-state tables
- validation data
- manuscript-ready evidence tables

---

## Integrity controls

Every selected source file was checked against its curated repository copy.

The final integrity audit confirmed:

- 0 missing files
- 0 source-file failures
- 0 size mismatches
- 0 manifest hash mismatches
- 0 source/copy SHA-256 mismatches
- 0 unexpected files
- 0 files >=100 MB

---

## Working-directory exclusion

The full Part 31 working directory was intentionally excluded from the GitHub release.

The working directory contains intermediate analyses, temporary outputs, historical files, and other materials that are not required for the curated reproducibility release.

The approximately 3.2 GB working directory was therefore not copied.

---

## Manuscript figures

No manuscript figure files were copied automatically during the repository build.

Three figure slots are reserved for manual upload:

- Figure 1
- Figure 2
- Figure 3

This avoids accidentally publishing an intermediate or incorrect figure version.

---

## Filename convention

Several final reproducibility files retain their original `PART_31_*` filenames.

These names correspond to selected final outputs from the project and are intentionally preserved for traceability.

Their presence does not mean that the complete Part 31 working directory has been included.

---

## Source preservation

The curated repository was assembled by copying selected source files.

The original project source files were not modified by the curation process.

---

## Audit records

The detailed final integrity audit is stored in the project audit directory:

`REPOSITORY_AUDIT/CURATED_REPOSITORY_FINAL_INTEGRITY_AUDIT.csv`

and:

`REPOSITORY_AUDIT/CURATED_REPOSITORY_FINAL_INTEGRITY_AUDIT.json`

---

## Release philosophy

The repository is intended to provide a compact and traceable reproducibility package.

It prioritizes:

1. final validated datasets
2. final manuscript results
3. selected computational code
4. provenance
5. integrity verification

Intermediate and redundant working files are intentionally excluded.
